# Mendix NL Design System

## Description

[......]

# Getting Started

1. Create an account at [Mendix](https://www.mendix.com/)
2. Install Mendix Studio Pro (MTS version):
   - Go to [Mendix Marketplace](https://marketplace.mendix.com/link/studiopro)
   - Filter for MTS
   - Download version 10.12.10 (MacOS beta or Windows)
3. Clone the project to your computer
   - note that Mendix Studio Pro is called studio Pro so if you cant find it just search studio pro
4. Open Mendix Studio Pro, select open file and locate the project, select the .mpr file to open the project
   - If prompted to convert the project click convert and wait, then proceed to start the project as usal, top right side green arrow
5. when the project is started, click "view app" (top right side) to open the project in the browser
6. Now login with these credentials :

**Username**: `MxAdmin` <br>
**Password**: `1`

## Installing the Optional Font

1. Obtain an access token for the font through your organization
2. Run the following commands in your terminal:
   ```bash
   export NPM_TOKEN=npm_a1b2c34f...  # Replace with your actual token
   ```
   ```
   pnpm run install
   ```
