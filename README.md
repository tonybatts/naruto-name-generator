# naruto-name-generator
Generate a random object that includes the name and a description of your favorite shows characters or receive an array of all characters and their descriptions. 

## Install
```$ npm install naruto-name-generator```
![naruto](https://github.com/tonybatts/naruto-name-generator/blob/main/naruto.png?raw=true)
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
