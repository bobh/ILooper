# ILooper
* THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
 * EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
 * MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
 * IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR
 * ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF
 * CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
 * WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

/** this application is based on @file paex_record.c
 @ingroup examples_src
 @brief Record input into an array; Save array to a file; Playback recorded data.
 @author Phil Burk  http://www.softsynth.com
 */


/*
 This program uses the WiringPi Library http://wiringpi.com/
 WiringPi is released under the GNU LGPLv3 license
 * wiringPi:
 *	Arduino compatable (ish) Wiring library for the Raspberry Pi
 *	Copyright (c) 2012 Gordon Henderson
 
 *
 * This program uses the PortAudio Portable Audio Library.
 * For more information see: http://www.portaudio.com
 * Copyright (c) 1999-2000 Ross Bencina and Phil Burk
 *
 *
 The Advanced Linux Sound Architecture (ALSA) comes with a kernel API and a 
 library API. 
 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 
 These files are compiled and linked with the portaudio library created for your     CPU and OS drivers.
 The library and "portaudio.h" should be in the build path. 
 The I/O pin specific code (WiringPi) is unique to the Raspberry Pi.
 
