# plcrashreporter

plcrashreporter forked from [Plausable Labs](https://www.plcrashreporter.org)

## DEBUFF

Because protobuf is an abomination, this fork removes it in it's entiretly and writes crash
reports as text files into the app sandbox: `~/Library/Logs/CrashReporter/`

Changes are guarded with `DEBUFF` macros to make future DIFFs with other forks easier.

## Changes

- Added this README.md
- Updated the Minimmum macOS requirement to 10.10 from 10.5 
- Assembly files now build correctly with `clang` instead of `gcc`
- `Dependencies/protobuf-2.0.3` removed
- Merged: https://github.com/plausiblelabs/plcrashreporter/pull/7
- Merged: https://github.com/plausiblelabs/plcrashreporter/pull/9 & 11
- Merged: https://github.com/plausiblelabs/plcrashreporter/pull/10
- Merged: https://github.com/plausiblelabs/plcrashreporter/pull/12

## Licenses

Except as noted below, PLCrashReporter is provided under the
following license:

    Copyright (c) 2008 - 2014 Plausible Labs Cooperative, Inc.
    All rights reserved.

    Permission is hereby granted, free of charge, to any person
    obtaining a copy of this software and associated documentation
    files (the "Software"), to deal in the Software without
    restriction, including without limitation the rights to use,
    copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the
    Software is furnished to do so, subject to the following
    conditions:

    The above copyright notice and this permission notice shall be
    included in all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
    EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES
    OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
    NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
    HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
    WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
    FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
    OTHER DEALINGS IN THE SOFTWARE.

Additional contributions have been made under the same license terms
as above, with copyright held by their respective authors:

    Damian Morris <damian@moso.com.au>
    Copyright (c) 2010 MOSO Corporation, Pty Ltd.
    All rights reserved.

    HockeyApp/Bitstadium
    Copyright (c) 2012 HockeyApp, Bit Stadium GmbH.
    All rights reserved.

    iStumbler Labs / Alf Watt <alf@istumbler.net>
    Copyright (c) 2018 Alf Watt
    All rights reserved.
