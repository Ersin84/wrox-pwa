# wrox-pwa

=== PWA — WroX Progressive Web App ===
Contributors: wrox
Donate link: https://wromo.com/pwa-wrox-progressive-web-app
Tags: PWA, Progressive Web Application
Requires at least: 5.6
Tested up to: 5.9
Stable tag: 1.0
Version: 1.0.0
License: GPLv3 or later
License URI: https://www.gnu.org/licenses/gpl-3.0.html

PWA plugin, handle /manifest.json and basic offline worker.

== Description ==

Progressive Web Apps (PWA) is a superior mobile web experience. They are installed on the phone like a normal app (web app) and can be accessed from the home screen.

The Progressive Web App from WroX-PWA is implemented very nicely. It is offline capable and can be added to the home screen.
WroX-PWA Link to the app: https://wromo.com/pwa-wrox-progressive-web-app

Wrox PWA makes it easy for you to convert your WordPress website into a Progressive Web App instantly!

Which browsers support PWA?
The major browsers Chrome, Edge, Opera, Firefox, Samsung Internet, Brave and a few others offer broad PWA support under Android. Android generally supports all three app modes of the Web App Manifest. In addition, PWAs can be distributed via the Play Store, the Samsung Galaxy Store and even the Amazon App Store.

Once this plugin is installed, users browsing your website from a supported mobile device will see a “Add To Home Screen” notice (from the bottom of the screen) and will be able to ‘install your website’ on the home screen of their device. Every page visited is stored locally on their device and will be available to read even when they are offline!

Wrox PWA is easy to configure, it takes less than a minute to set-up your Progressive Web App!


== Installation ==

There are many ways to install this plugin:

= 1. The super easy way =
1. In your Admin, go to menu Plugins > Add
1. Search for `wRox PWA`
1. Click to install
1. Activate the plugin

= 2. The easy way =
1. Download the plugin (.zip file) on the right column of this page
1. In your Admin, go to menu Plugins > Add
1. Select button `Upload Plugin`
1. Upload the .zip file you just downloaded
1. Activate the plugin

= 3. The old and reliable way (FTP) =
1. Upload `wrox-pwa` folder to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress

== Frequently Asked Questions ==

= How to change meta theme-color? =

First plugin try to get `theme_mod` with default set to `f0f0f0`:

`get_theme_mod( 'background_color', 'f0f0f0');`

Please use `wrox_pwa_configuration_theme_color` filter to change this value:

`
add_filter( 'wrox_pwa_configuration_theme_color', function( $color ) {
    return '#f20';
}
`
As returned value you can return any valid color, but remember alpha value will be ignored (for rgba, hsla or hex with alpha).


== Screenshots ==

1. General configuration.
2. Generic configuration.
3. Apple configuration.
4. Microsoft configuration.

== Changelog ==



##### 1.0 (2022-02-01)


= 1.0 (2022-01-18) =
* Init.

== Upgrade Notice ==

