# VSCode React Native Snippets

This repository contains few of the custom snippets that i use in my react native development using vscode

## Setup Instructions (VSCODE)

- Open Visual Studio Code

- CODE > PREFERENCES > USER SNIPPETS > **javascriptreact.json/jsx-attr.json/jsx.json**

- Copy the code from this repository into that file.

## Issues :

- In case your javascriptreact.json snippets don't work, try and copy it into :

- CODE > PREFERENCES > USER SNIPPETS > **javascript.json**

## javascript.json/javascriptreact.json Snippets

```sh

rn  - Create React Native Default Code
rnavi  - Create React Native with React Navigation (App.js)
rnaviDrawerNavigator - Create React Native with React Navigation (CreateDrawerNavigator)
rnaviBottomTabNavigator -  Create React Native with React Navigation (createBottomTabNavigator)
rnaviStackNavigator - Create React Native with React Navigation (createBottomTabNavigator)
imrnavigation - Import React Navigation
imrnvicons - Import React Native Vector Icons
imrnconst - Import React Native constant.js file
imrnstyles - Import React Native styles.js file
rndimen - Create React Native Dimensions
rnstate - Create React Native state
rncdm - Create React Native componentDidMount
rncomp - Create React Native Class Component
rnfcomp - Create React Native Functional Component
rnss - Create React Native StyleSheet
clog   - console.log
clogJSON   - JSON console.log

```

## jsx-attr.json -> JSX Attribute Snippets

```sh
(from Unsure Programmer )
rnajc - alignItems:'center',justifyContent:'center'
```

## jsx.json -> JSX Snippets

```sh
<Button - <Button title='${1:title}' onPress={()=>${2:this.props.navigation.navigate(\"Screen\")}}/>
<View - <View style={[${1:mainStyle.container}, ${2:mainStyle.middleCenter}]}></View>
<Text - <Text style={[${1:mainStyle.text}, ${2:mainStyle.caption}]}>${3:componentName}</Text>
<Icon - <Icon name='${1:md-menu}' size={${2:30}}/>
```
