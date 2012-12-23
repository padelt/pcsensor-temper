
This is software found rather uncommented on the internet (see below for the actual source)
and then changed to allow for multiple devices to be queried.

It works with TEMPer devices that present a USB ID like this: `0c45:7401 Microdia`

Mine was an [M-Ware ID7747](http://www.m-ware.de/m-ware-usb-thermometer-40--120-c-emailbenachrichtigung-id7747/a-7747/).

# ORIGIN

Downloaded from [here](http://www.isp-sl.com/pcsensor-1.0.0.tgz)
as seen on [Google+](https://plus.google.com/105569853186899442987/posts/N9T7xAjEtyF).

# LICENSE

From the source:

	/*
	 * pcsensor.c by Philipp Adelt (c) 2012 (info@philipp.adelt.net)
	 * based on Juan Carlos Perez (c) 2011 (cray@isp-sl.com)
	 * based on Temper.c by Robert Kavaler (c) 2009 (relavak.com)
	 * All rights reserved.
	 *
	 * Temper driver for linux. This program can be compiled either as a library
	 * or as a standalone program (-DUNIT_TEST). The driver will work with some
	 * TEMPer usb devices from RDing (www.PCsensor.com).
	 *
	 * This driver works with USB devices presenting ID 0c45:7401.
	 *
	 * Redistribution and use in source and binary forms, with or without
	 * modification, are permitted provided that the following conditions are met:
	 *     * Redistributions of source code must retain the above copyright
	 *       notice, this list of conditions and the following disclaimer.
	 * 
	 * THIS SOFTWARE IS PROVIDED BY Philipp Adelt (and other contributors) ''AS IS'' AND ANY
	 * EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
	 * WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
	 * DISCLAIMED. IN NO EVENT SHALL Philipp Adelt (or other contributors) BE LIABLE FOR ANY
	 * DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
	 * (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
	 * LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND
	 * ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
	 * (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
	 * SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
	 * 
	 */

