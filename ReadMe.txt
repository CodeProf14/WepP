WebP Photoshop plug-in
by Brendan Bolles <brendan@fnordware.com>

Version 0.5b9 - 16 December 2015


Intro
=====

WebP is a still image format developed by Google.  It features good lossless and lossy compression, usually beating both JPEG and PNG in size/quality comparisons.  It is based on the VP8 video codec, which Google acquired and released as open source.


Installation
============

Copy the WebP.plugin (Mac) or WebP.8bi (Windows) to the Photoshop plug-ins directory.  On Windows, make sure to choose 32-bit or 64-bit based on the version of Photoshop you're using.


Usage
=====

The plug-in lets you select either lossy or lossless compression, and set the desired quality level from 0-100.  WebP supports an alpha channel, which can come from either transparency or a channel in the Channels palette.

When writing a file with transparency, the "Alpha Cleanup" option will blacken out the RGB of any totally transparent pixels, improving compression performance.

When saving a lossy image with an alpha channel, the "Lossy Alpha" option will also compress the alpha with your selected quality setting.  Otherwise the alpha will be saved losslessly.

When "Save Metadata" is checked, the ICC profile, EXIF, and XMP metadata will be embedded in the WebP if available.

When opening an WebP file, hold down the Shift key to choose to apply an Alpha channel as transparency or place it in the Channels palette.  The defaults can be changed and the user can set a preference to open this dialog whenever an alpha is present.


Open Source
===========

Like WebP itself, this plug-in is open source.  See the code and participate here:

https://github.com/fnordware/AdobeWebM 


License
=======

Released under the BSD license:

Copyright (c) 2013, Brendan Bolles
All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.



This plug-in uses libwebp under this license:

Copyright (c) 2010, Google Inc. All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

* Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

* Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

* Neither the name of Google nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

