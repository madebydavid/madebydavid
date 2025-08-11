## Hi, I'm David

I am a developer building tools for developers making Godot mobile games.

I am working on [ShipThis CLI](https://github.com/shipth-is/cli) - a command-line tool for building and uploading your Godot mobile games to the Apple App Store and Google Play.

```bash
# Install
npm install -g shipthis

# Authenticate (creates an account if one does not exist)
shipthis login

# Run the interactive setup wizard to configure fully automated building
# - Creates/import a KeyStore and generates a Service Account API key
shipthis game wizard android

# Do the same for iOS
# - Generate a iOS signing certificate, provisioning profile, and App Store Connect API key
shipthis game wizard ios

# Build and upload to TestFlight / Google Play with one command
shipthis game ship

```
