Android app for the [Cari Harga Barang][1] website

Run the following after checkout (Cordova > 3):

    cordova platform add android

Issues
======
* Phonegap can't open existing sqlite database. Workaround:-
    - http://www.raymondcamden.com/index.cfm/2012/7/27/Guest-Blog-Post-Shipping-a-populated-SQLite-DB-with-PhoneGap
    - http://www.corporatezen.com/shipping_prepopulated_database_with_phonegap

* Cordova-SQLitePlugin has issue on android < 2.3.3:-
    - https://github.com/chbrody/Cordova-SQLitePlugin/issues/29
    - Workaround - delete lines in SQLitePlugin.java that start with:-

        // for old Android SDK remove lines from HERE:

[1]:http://harga.smach.net/
