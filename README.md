# wmarsha Extreme serialization tool

# Compare test with google.protobuf

Marshal speed is 9 to 33 times that of pb

Unmarsha speed is 105 ～ 263 times of pb

The byte stream obtained by Marshal is 27% ～ 72% of pb

Memory usage is 21% ～ 93% of pb

Marshal's CPU usage is 102% ～ 320% of pb

Unmarsha's CPU usage is 79% ～ 211% of pb

Marshal and Unmarsha's CPU usage is 79% to 320% of pb, and the probability of being greater than 100% is 73%, and the optimization work is still in progress.

Remarks: At present, the nesting structure has not been completed, and there is no test data.

Test environment and data, test cases will be uploaded together with the release.

# At present, only the implementation version of go has been completed, and subsequent languages such as c / c ++, java, js, python, c #, lua, and typescript will be supported.
# Open source release work is continuing, so stay tuned ...
