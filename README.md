# vuetify-otp-bug

Repo created to showcase Vuetify's v-otp-input bug with autofill.

- Vuetify Version: 3.6.10
- Vue version: 3.4.30

## How to reproduce

- Install dependencies with `yarn`
- Boot the project with `yarn dev`
- Add a OTP secret to a browser password manager. You can use example secret "VCKIPQKJKYO6O3LU". Currently it's happening in 1Password v2.25.1
- Click on "Autofill"
- Check console logs and "Current input" label

Note that manually input works fine, and copying and pasting also works fine.