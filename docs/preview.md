# Preview

Parameter | Type | Default | Description
------ | --------- | ------- | --------
muteOnPreviewMode | boolean | `true` | When playing in preview mode, turn on/off sound
fadeInAudioStart | number | `0` | If `fadeInAudioInterval` is set, time when it starts fading in
fadeInAudioInterval | number | `0` | When playing media, time interval to fade in audio (must be greater than zero)
fadeOutAudioStart | number | `0` | If `fadeOutAudioInterval` is set, time when it starts fading out
fadeOutAudioInterval | number | `0` | When playing media, time interval to fade out audio (must be greater than zero)
fadePercent | number | `0.2` | Percentage in which media will fade in/out (in decimals, where 0.2 = 20%, 1 = 100%) 
pauseOnlyOnPreview | boolean | `false` | Whether reset or not the media when on preview mode