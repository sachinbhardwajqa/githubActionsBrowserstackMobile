/* Note the "app_url" value for the sample app. This value uniquely identifies the app on BrowserStack. */
{
    "app_url":"bs://c700ce60cf13ae8ed97705a55b8e022f13c5827c"
}
/* In your test script, use this "app_url" value to specify the application under test using the "app" capability. During test execution, the sample app will automatically be installed and launched on the device being tested. */

caps.setCapability("app", "bs://c700ce60cf13ae8ed97705a55b8e022f13c5827c")