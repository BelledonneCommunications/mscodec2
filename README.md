**CAUTION: this git repository is no longer updated. The project has been merged into the linphone-sdk ([Gitlab](https://gitlab.linphone.org/BC/public/linphone-sdk), [Github](https://github.com/BelledonneCommunications/linphone-sdk)) git repository and will continue his life there.**

**Versions up to 5.4 (included) are still kept into this repository, that will remain active on release/5.4 branch until the end of life of release 5.4.**

This package supplies the mediastreamer plugin for the codec2 audio
codec, which is necessary to use codec2 with Linphone.  The package
does not contain the codec, which must be obtained separately.

More information on codec2 at http://rowetel.com/codec2.html

Codec2 is distributed by David Rowe under GNU Lesser General Public License (LGPL)

This package use the 3200 bits/s mode of codec2 by default but it may
also be tuned to use the 2400 bits/s mode. It was tested on stable branch 0.3
of the codec2 library.
