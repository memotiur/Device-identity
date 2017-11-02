        String android_id = Settings.Secure.getString(getContentResolver(), Settings.Secure.ANDROID_ID);
        SharedPreferenceClass sharedPreferenceClass = new SharedPreferenceClass();
        sharedPreferenceClass.saveDeviceUniqueid(getApplicationContext(), android_id);
