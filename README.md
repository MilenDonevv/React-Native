# React-Native

1) We're importing 2 important components from the react-native library - View, Text

import React from 'react'
import {View, Text} from 'react-native'


const App = () => {
    return (
        <View>
            <Text style={styles.text}>Hello React Native</Text>
        </View>
    )
}

We have also a **StyleSheet** utility to optimize performance

const styles = StyleSheet.create({
    text: {
        fontSize: 24,
        color: 'blue',
        fontWeight: 'bold'
    }
})

We have **NativeWind** as equivalent to **Tailwind CSS**

- **View** Component - similar to <div> in HTML but with some functionality specific to mobile apps.

- it Uses Flexbox layout by default

- **TouchableOpacity** - great for buttons
- **TouchableHighlight** - makes views respond to a touch in an unique way
- **TouchableWithoutFeedback** - for clickable elements with no visual feedback when pressed.
  It is especially useful for creating links or images which usually don't require any additional styling

- **ActivityIndicator** - shows a spinner or a loading indicator
- **Button** - a simple button with a few additional options such as showing when pressed.
- **Flatlist** - perfect for long lists of items which need to be scrolled

It is like the 'map' function in React, but it has some extra features like: **optimized scroll performance** and
**items separation**

For larger lists it's better to use the **Flatlist**, whereas for smaller list - use map()

- **ScrollView** - a magic box that can hold multiple components and views, providing a scrolling container for them - suitable for large content or list of items

- **SafeAreaView** - provides a safe zone for content rendering without being covered by anything like device's status bar. HIGHLY RECOMMENDED because it is working on ANY DEVICE

- **Image** - rendering images

- **ImageBackground** - images go as a background and other elements are layered on top of them
- **Modal** - rendering modals
- **Alert** - rendering alerts
- **Switch** - for Toggling stuff
- **StatusBar** - showing what the status bar should look like - light or dark






