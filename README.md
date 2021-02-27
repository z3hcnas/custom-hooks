#NOTAS

*ueForm*


code of the component


    const [{id, name}, handleInputChange, reset] = useForm({ id: user.id, name: user.name })

    const submitForm = (e) => {
        e.preventDefault();

        setUser({
            id,
            name
        })
        reset()

    }

the name of the input is the name of the propiety for the values


*useFetch*

parameter = url
returns error, data, loding
