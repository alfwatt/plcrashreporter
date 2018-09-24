# plcrashreporter

plcrashreporter forked from [Plausable Labs](https://www.plcrashreporter.org)

## DEBUFF

Because protobuf is an abomination this fork removes it in it's entiretly and writes crash
reports as text files into the app sandbox: `~/Library/Logs/CrashReporter/`

This also means that several accessory binaries and steps can be removed.

## Changes

- Added this README.md
- Updated the Minimmum macOS requirement to 10.10 from 10.5 
- Assembly files now build correctly with `clang` instead of `gcc`
- `Dependencies/protobuf-2.0.3` removed
- Removed Depricated Gestalt Checks

## Licenses



PLCrashReporter - https://www.plcrashreporter.org

     * Author: Landon Fuller <landonf@plausiblelabs.com>
     *
     * Copyright (c) 2008-2009 Plausible Labs Cooperative, Inc.
     * All rights reserved.
     *
     * Permission is hereby granted, free of charge, to any person
     * obtaining a copy of this software and associated documentation
     * files (the "Software"), to deal in the Software without
     * restriction, including without limitation the rights to use,
     * copy, modify, merge, publish, distribute, sublicense, and/or sell
     * copies of the Software, and to permit persons to whom the
     * Software is furnished to do so, subject to the following
     * conditions:
     *
     * The above copyright notice and this permission notice shall be
     * included in all copies or substantial portions of the Software.
     *
     * THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
     * EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES
     * OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
     * NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
     * HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
     * WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
     * FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
     * OTHER DEALINGS IN THE SOFTWARE.

PLCrashLogWriterEncoding.c - TO BE REMOVED

     * Copyright 2008, Dave Benson.
     * Copyright 2008 - 2009 Plausible Labs Cooperative, Inc.
     * 
     * Licensed under the Apache License, Version 2.0 (the "License");
     * you may not use this file except in compliance with
     * the License. You may obtain a copy of the License
     * at http://www.apache.org/licenses/LICENSE-2.0 Unless
     * required by applicable law or agreed to in writing,
     * software distributed under the License is distributed on
     * an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
     * KIND, either express or implied. See the License for the
     * specific language governing permissions and limitations
     * under the License.
