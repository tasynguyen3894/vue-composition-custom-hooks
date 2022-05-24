# Vue custom hooks

Some useful Vue custom hooks

## Installation

Using npm or yarn
```
# npm
npm install vue-composition-custom-hooks

# yarn
yarn add vue-composition-custom-hooks
```

## Available Hooks

- useCopyToClipboard.js
- useNetworkStatus.js
- useOnClickOutside.js
- useScrollToBottom.js
- useStorage.js
- useTheme.js
- useTimer.js
- useViewport.js
- useVisibility.js
- useWindowResize.js

## To use them

```js
import useNetworkStatus from 'vue-composition-custom-hooks';

export default {
  setup() {
    useNetworkStatus((status) => {
      console.log(`You are ${status}`);
    })
  }
}
```

## About me

My name is **Sang**, just a lazy web developer in Vietnam. I hope custom hooks I created will useful with you.

## License

MIT. See [LICENSE](LICENSE.txt) for more details.
