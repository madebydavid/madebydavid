## Hi, I'm David

I am a developer building tools for developers making Godot mobile games.

I am working on [ShipThis](https://github.com/shipth-is/cli) - a command-line tool for building and publishing your **Godot** mobile games to the **Apple App Store** and **Google Play**.

```bash
# Install the ShipThis CLI
npm install -g shipthis

# Authenticate with ShipThis
shipthis login
# - Creates a ShipThis account if one does not exist

# Run the interactive Android setup wizard
shipthis game wizard android
# - Creates or imports an Android Keystore
# - Generates a Google Cloud project
# - Enables Google Play Developer API
# - Creates a Service Account linked to your Google Play Developer account
# - Generates and downloads a Service Account API key

# Run the interactive iOS setup wizard
shipthis game wizard ios
# - Generates an iOS signing certificate
# - Generates an App and Bundle ID
# - Generates a provisioning profile
# - Synchronises the permissions (entitlements/capabilities)
# - Generates and downloads an App Store Connect API key

# Build and upload your game
shipthis game ship
# - Uploads your code to the build server
# - Compiles and signs the binary with the required certificates
# - Submits to Google Play and/or App Store Connect
# - Distributes to TestFlight (for iOS) or internal testing (for Google Play)

```
