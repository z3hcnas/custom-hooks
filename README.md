#NOTAS

useForm

*code of the component*

<const [{id, name}, handleInputChange, reset] = useForm({ id: user.id, name: user.name })

    const submitForm = (e) => {
        e.preventDefault();

        setUser({
            id,
            name
        })
        reset()

    }
