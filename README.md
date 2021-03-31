# naruto-name-generator
Generate a random object that includes the name and a description of your favorite shows characters or receive an array of all characters and their descriptions. 
Click the GIF on [this page](https://www.jenreyes.design/about) for a live demo.

## Install
```$ npm install naruto-name-generator```
<img align="right" src="https://github.com/tonybatts/naruto-name-generator/blob/main/images/%20naruto-standing.png">

## Usage
```js
import { naruto } from "naruto-name-generator"

naruto.random()
//=> {name: "Sasuke Uchiha", description: "..."}

naruto.all
//=> [{...}, {...}, {...}]
```
## API
### .random()
Type: ```Function```

Random Naruto character name and description.

### .all
Type: ```string[]```

List of all Naruto names and their descriptions.
