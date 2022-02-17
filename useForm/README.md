# useForm Hook

Ejemplo de uso:

```
const initialForm = {
    id: 112233,
    name: '',
    email: '',
    age: 0

};

const [  formValues, handleInputChange, reset ] = useForm( initialForm );
```

```
useForm(?);
```

- El hook recibe un initialForm
