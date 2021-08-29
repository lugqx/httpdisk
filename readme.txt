
    Virtual disk driver over HTTP for Windows.
    Copyright (C) 2006-2020 Bo Brantén.

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 2 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.

    Windows and Windows NT are either registered trademarks or trademarks of
    Microsoft Corporation in the United States and/or other countries.

    Please send comments, corrections and contributions to bosse@acc.umu.se.

    The most recent version of this program is available from:
    http://www.acc.umu.se/~bosse/

    Revision history:

   10.2 2020-05-27
       The drivers are testsigned, you can allow Windows to load testsigned
       drivers with the command "bcdedit /set testsigning on".

   10.1 2015-12-28
       Ksocket is now built as a library, this will make it easier to
       maintain and use for more than one project.

   10. 2015-12-16
       Improved compatibility with Visual Studio Community 2015 and
       Windows Driver Kit (WDK) 10.

    9. 2015-09-24
       Minor change, can be compiled with Visual Studio Community 2015 and
       Windows Driver Kit (WDK) 10.

    8. 2015-04-29
       Support for more ioctl:s.
       Can be compiled with both DDK and WDK.
       Improved error handling.
       Improved debug prints.

    7.02 2015-04-25
       Small bug fix for mounting non CD/DVD images.

    7.01 2015-04-17
       Small update to pass all code analyzes in WDK 7.1.0.

    7. 2009-10-21
       Small bug fix for CD-images on Windows Vista and Windows 7.
       Support for 64-bit systems.

    6. 2009-10-15
       Allow to mount images without administrative privileges by
       Konstantin Vlasov.

    5. 2009-04-12
       Support for DVD images with the UDF file system.
       Can be compiled with the WDK.

    4. 2008-07-11
       Minor changes.

    3. 2006-03-08
       Small bug fix in handling of receive data length.

    2. 2006-03-05
       Added support for persistent connections.

    1. 2006-02-11
       Initial release.
