OpusfileSharp - A C# wrapper for libopusfile

Released under the MIT license (see LICENSE.txt)

This library wraps libopusfile and exposes it as a simple class.
op_open_callbacks is used underneath to read an opus file from any .NET Stream.
OggOpusFile instances MUST be disposed manually; finalization will not free
the underlying resources. In DEBUG builds, a finalizer will be compiled in
that will report any undisposed instances.
