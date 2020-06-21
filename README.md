# www.xoso.com.vn
https://xoso.com.vn/xo-so-mien-nam/xsmn-p1.html
Force update uid state when pending uid state is applied Before the state was update lazily when someone interacted with appopsmanager. Since Q the the uid state might change depending on the procState and hence we might need to trigger the opChanged callbacks when the procState is applied. Bug: 148180766 Test: (on master) atest CtsAppOpsTestCases:android.app.appops.cts.ForegroundModeTest Change-Id: I99720a372db6e79eaba30e4563c09e009cffe86f Merged-In: Id974769a4e9d89c01890b7557dd93f8444a3908f (cherry picked from commit ab9be4fdb63bf30831fd2e05be1315e6c7f067ae) services/core/java/com/android/server/appop/AppOpsService.java[diff]

1 file changed

tree: 82b77972a0f52915eb96027f262c09ddd06a441d

.gitignoreAndroid.bpAndroid.mkCleanSpec.mkMODULE_LICENSE_APACHE2NOTICEPREUPLOAD.cfgapct-tests/api/cmds/config/core/data/docs/drm/graphics/jarjar_rules_hidl.txtkeystore/libs/location/lowpan/media/native/nfc-extras/obex/opengl/packages/pathmap.mkproto/rs/samples/sax/services/startop/telecomm/telephony/test-base/test-legacy/test-mock/test-runner/tests/tools/wifi/

Powered by Gitiles| Privacytxtjson

