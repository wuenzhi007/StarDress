# Welcome to your new ignited app!

> The latest and greatest boilerplate for Infinite Red opinions

This is the boilerplate that [Infinite Red](https://infinite.red) uses as a way to test bleeding-edge changes to our React Native stack.

- [Quick start documentation](https://github.com/infinitered/ignite/blob/master/docs/boilerplate/Boilerplate.md)
- [Full documentation](https://github.com/infinitered/ignite/blob/master/docs/README.md)

## Getting Started

```bash
yarn install
yarn start
```

To make things work on your local simulator, or on your phone, you need first to [run `eas build`](https://github.com/infinitered/ignite/blob/master/docs/expo/EAS.md). We have many shortcuts on `package.json` to make it easier:

```bash
yarn build:ios:sim # build for ios simulator
yarn build:ios:dev # build for ios device
yarn build:ios:prod # build for ios device
```

### `./assets` directory

This directory is designed to organize and store various assets, making it easy for you to manage and use them in your application. The assets are further categorized into subdirectories, including `icons` and `images`:

```tree
assets
├── icons
└── images
```

**icons**
This is where your icon assets will live. These icons can be used for buttons, navigation elements, or any other UI components. The recommended format for icons is PNG, but other formats can be used as well.

Ignite comes with a built-in `Icon` component. You can find detailed usage instructions in the [docs](https://github.com/infinitered/ignite/blob/master/docs/boilerplate/app/components/Icon.md).

**images**
This is where your images will live, such as background images, logos, or any other graphics. You can use various formats such as PNG, JPEG, or GIF for your images.

Another valuable built-in component within Ignite is the `AutoImage` component. You can find detailed usage instructions in the [docs](https://github.com/infinitered/ignite/blob/master/docs/Components-AutoImage.md).

How to use your `icon` or `image` assets:

```typescript
import { Image } from 'react-native';

const MyComponent = () => {
  return (
    <Image source={require('../assets/images/my_image.png')} />
  );
};
```

## Running Maestro end-to-end tests

Follow our [Maestro Setup](https://ignitecookbook.com/docs/recipes/MaestroSetup) recipe.

## Next Steps

### Ignite Cookbook

[Ignite Cookbook](https://ignitecookbook.com/) is an easy way for developers to browse and share code snippets (or “recipes”) that actually work.

### Upgrade Ignite boilerplate

Read our [Upgrade Guide](https://ignitecookbook.com/docs/recipes/UpdatingIgnite) to learn how to upgrade your Ignite project.

## Community

⭐️ Help us out by [starring on GitHub](https://github.com/infinitered/ignite), filing bug reports in [issues](https://github.com/infinitered/ignite/issues) or [ask questions](https://github.com/infinitered/ignite/discussions).

💬 Join us on [Slack](https://join.slack.com/t/infiniteredcommunity/shared_invite/zt-1f137np4h-zPTq_CbaRFUOR_glUFs2UA) to discuss.

📰 Make our Editor-in-chief happy by [reading the React Native Newsletter](https://reactnativenewsletter.com/).



## backup info
    █ Creating StarDress using Ignite 10.1.9
    █ Powered by  ∞ Infinite Red  (https://infinite.red)
    █ Package Manager: yarn
    █ Bundle identifier: com.star.stardress
    █ Path: /home/david/Work/StarDress/StarDress
    ────────────────────────────────────────────────────
   
    🖨  3D-printing a new React Native app
    🎨 Getting those last few details perfect
    🧶 Installing yarn dependencies (wow these are heavy)
    ⚙️ Configuring app.json
    🛠️ Generating native template via Expo Prebuild
    🛠️ Removing fancy demo markup
    🌳 Removing MobX-State-Tree markup
    🧽 Cleaning up
    🗄  Backing everything up in source control
   
    ────────────────────────────────────────────────────
   
    Ignited StarDress in 463.37s  🚀 
    
    For next time, here are the Ignite options you picked:
      npx ignite-cli new StarDress \
        --bundle=com.star.stardress \
        --git \
        --install-deps \
        --packager=yarn \
        --target-path=/home/david/Work/StarDress/StarDress \
        --remove-demo=false \
        --new-arch=false \
        --workflow=cng \
        --no-timeout=false \
        --state=mst 
    
    ────────────────────────────────────────────────────
    
    To run in Android, make sure you've followed the latest
    react-native setup instructions. You reference them at:
    https://reactnative.dev/docs/environment-setup
    
    ────────────────────────────────────────────────────
    
    Need additional help?
    
    Join our Slack community at http://community.infinite.red.
    
    ────────────────────────────────────────────────────
    
    Now get cooking! 🍽
      cd /home/david/Work/StarDress/StarDress
      yarn android
    
