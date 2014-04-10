Copyright (c) Dapper Apps.  All rights reserved.
Use of this source code is subject to the terms of the Dapper Apps license 
agreement under which you licensed this sample source code and is provided AS-IS.
If you did not accept the terms of the license agreement, you are not authorized 
to use this sample source code.  For the terms of the license, please see the 
license agreement between you and Dapper Apps.

To see the article about this app, visit http://www.dapper-apps.com/DapperToolkit

DapperBinarySerializer
==================

A custom Binary Serializer implementation for Windows Phone 8

Represents a class that performs BinarySerialization on a number of different objects.
Supported objects include:
  The safe primitive types, e.g. Boolean, Byte, SByte, Int16, UInt16, Int32, UInt32, Int64, UInt64, Char, Double, and Single.
  All of the primitive array types.
  String type.
  WriteableBitmap and derived types.
  IList<string> and derived types.
  IList<WriteableBitmap> and derived types.
  
  
TODO Write code to recursively serialize IList<Ilist<Ilist...
TODO Any class that might be serialized must be marked with the SerializableAttribute
