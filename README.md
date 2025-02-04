# Instagram-Mobile-Security-Reversed
I've Fully Reverse Engineered the Following Values from Instagram Android / Google Attestation Services:

- Playstore Integrity (https://i.instagram.com/api/v1/attestation/create_android_playintegrity/)
  - app_scoped_device_id
- Android Keystore (https://i.instagram.com/api/v1/attestation/create_android_keystore/)
  - app_scoped_device_id
  - key_hash
- [SafetyNet](https://developers.google.com/android/reference/com/google/android/gms/safetynet/SafetyNet)
  - safetynet_token
  - safetynet_response
- Instagram Signatures
  - encrypted_password
  - caa_core_data_encrypted
  - INTERNAL__latency_qpl_instance_id
  - Any Other Value
- Lowlevel Requests
  - MQTT Requests
  - logging_client_events Requests
- Bloks Auto Updater
  - Systematically Disassemble, Deobfuscate, and extract the newest bloks_versioning_id upon every update
 
**I've fully reversed Instagram Android and am selling my unflagged Account Creator, with all features above integrated, contact me for info: [Telegram](https://t.me/f8956c44e702e1584cc1b45b7f57c488)**
