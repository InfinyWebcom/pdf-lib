# Build Overview

This project utilizes Node 12 and Yarn for package management.

## Command

```bash
# Install Node.js version 12
nvm install 12

# Switch to Node.js 12
nvm use 12

# Install Yarn globally
npm install -g yarn

# Install all project dependencies
yarn install

# Build the project
yarn build
```

### Troubleshooting

If you are facing issues with the build, it's most probably because of the Node.js version being used when building.

While compiling, I ran into a situation where I mistakenly installed Node.js in Linux using the system's package manager, and then ran ```yarn install```.

If you see a system entry in the output of ```nvm ls```, please remove it and try again, ensuring you are only using the Node version installed via NVM.