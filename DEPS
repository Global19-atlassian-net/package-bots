# Copyright (c) 2014, the Dart project authors.  Please see the AUTHORS file
# for details. All rights reserved. Use of this source code is governed by a
# BSD-style license that can be found in the LICENSE file.

vars = {
  # We _don't_ inline this to allow the bots to use the mirror.
  "googlecode_url": "http://%s.googlecode.com/svn",
  "gsutil_rev" : "@33376",
  "d8_rev" : "@39739",
  "firefox_jsshell_rev" : "@35614",
}

deps = {
  "dart/tools":
      (Var("googlecode_url") % "dart") + "/branches/bleeding_edge/dart/tools",
  #### temporary until we fix configs ###
  "dart/runtime/tests/vm":
      (Var("googlecode_url") % "dart") +
       "/branches/bleeding_edge/dart/runtime/tests/vm",
  "dart/tests/co19":
      (Var("googlecode_url") % "dart") +
      "/branches/bleeding_edge/dart/tests/co19",
  #### end temporary ###
  "dart/third_party/d8":
      (Var("googlecode_url") % "dart") + "/third_party/d8" + Var("d8_rev"),
  "dart/third_party/gsutil":
      (Var("googlecode_url") % "dart") + "/third_party/gsutil" +
       Var("gsutil_rev"),
  "dart/third_party/firefox_jsshell":
      (Var("googlecode_url") % "dart") + "/third_party/firefox_jsshell" +
       Var("firefox_jsshell_rev"),
}
