# naruto-name-generator
Generate a random object that includes the name and a description of your favorite shows characters or receive an array of all characters and their descriptions. 

## Install
```$ npm install naruto-name-generator```
![naruto](https://drive.google.com/file/d/1-0g-hN0j-H0Hp-G739_Je5X6WsEp2bxQ/view?usp=sharing)
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
