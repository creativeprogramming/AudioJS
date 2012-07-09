AudioJS
--------
Fork of [VideoJS.com](http://videojs.com) for audio, with support for themes.

<a href="http://jedfoster.github.com/AudioJS/">Check out the demo</a> for an example of how to use it.

Based on [VideoJS.com](http://videojs.com)


Example jQuery plugin:

    if (window.jQuery) {
      (function($) {
        $.fn.AudioJS = function(options) {
          this.each(function() {
            AudioJS.setup(this, options);
          });
          return this;
        };
        $.fn.player = function() {
          return this[0].player;
        };
      })(jQuery);
    }


Audio sample is ["Crookshanks" by Palace Cat](http://palacecat.bandcamp.com/track/crookshanks), via [duplokat](http://duplokat.tumblr.com/post/12695092003/geek-friday-ringtone)