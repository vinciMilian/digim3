Lembretes:

Tentar adicioanr modelo de usuário:

```
const mongoose = require('mongoose')
const Schema = require('mongoose.Schema')

const userModel = new Schema({
    nome:{
        type: String,
        required: true
    },
    email:{
        type: String,
        required: true
    },
    password:{
        type: String,
        required: true
    }
});

mongoose.model('User', userModel);
```
