simulatorTestReceipt
====================

Displays the receipt of an app to help me test addition to r2d2b2g

To test the receipt installation:

1. `git clone git://github.com/nickdesaulniers/simulatorTestReceipt.git && cd simulatorTestReceipt`
2. `python server.py`
3. start simulator
4. remove previous instances of installations of this app
5. Test hosted app by putting `http://localhost:3000/manifest.webapp` and clicking Add Manifest.  Receipt should appear in green.
6. Remove app
7. Test generated app by putting `http://localhost:3000/index.html` and clicking Add URL.  Receipt should appear in green.
8. Remove app
9. Test packaged app by clicking Add Directory then navigating to `simultatorTestReceipt/manifest.webapp`.  Receipt should appear in green.
10. Remove app
11. Kill python server
