# BarangayConnect — Official Release Distribution

Public Android APK distribution channel for the **BarangayConnect** ecosystem (Barangay II — Poblacion, Pontevedra).

> **Note:** This repository hosts **compiled release binaries only** (under [GitHub Releases](https://github.com/donaron/barangay-connect-releases/releases)). Application source code, environment configuration, and signing credentials are kept strictly private.

## Applications Distributed Here

| App | Package ID | Binary Asset |
| :--- | :--- | :--- |
| **BarangayConnect Unified** | `com.barangayconnect.resident.barangay_resident_app` | `BarangayConnect_Unified_App.apk` |
| **Barangay Central Admin** | `com.example.barangay_connect` | `BarangayConnect_Central_Admin_App.apk` |
| **Barangay Health Admin** | `com.barangayconnect.healthcareadmin.barangay_healthcare_admin_app` | `BarangayConnect_Healthcare_Admin_App.apk` |
| **Barangay Tanod Admin** | `com.barangayconnect.tanodadmin.barangay_tanod_admin_app` | `BarangayConnect_Tanod_Admin_App.apk` |
| **Tanod Field Terminal** | `com.barangay.tanod.barangay_tanod_app` | `BarangayConnect_Tanod_Field_App.apk` |

## Integrity & Dual Update Mode

- **Primary CDN:** GitHub Releases direct HTTPS download + automatic in-app **SHA-256 checksum verification** before Android package installation.
- **OTA Patches:** Shorebird Code Push delivers lightweight Dart patches between APK builds.
- **Backup Mirror:** Preserved Google Drive direct download links remain available as a one-tap fallback inside the Portal Launcher & Update Modal.
