# ClipBoard<br />
**Created Date:** 9/24/2014<br />
**Last Updated:** 9/24/2014<br />
**Description:** A Traditional Synergy class that provides basic copy/paste interaction with the Windows clipboard.<br />
**Platforms:** Windows<br />
**Products:** Synergy DBL<br />
**Minimum Version:** 10.1.1<br />
**Author:** Steve Ives
<hr>

**Additional Information:** Notes for use: The class requires access to the window handle (HWND) of a
window to which the clipboard can be captured, and the only
way to get the HWND in a Traditional synergy application is
via the Synergy Windows API (or UI Toolkit which uses the
Synergy Windows API). For this reason the clipbaord routines
will not work unless you AT LEAST call %W_INIT.

*****************************************************************************

Copyright (c) 2014, Synergex International, Inc.
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

* Redistributions of source code must retain the above copyright notice,
this list of conditions and the following disclaimer.

* Redistributions in binary form must reproduce the above copyright notice,
this list of conditions and the following disclaimer in the documentation
and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE
LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR
CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF
SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS
INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN
CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE)
ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE
POSSIBILITY OF SUCH DAMAGE.
Update Date	
9/24/2014
 	 
