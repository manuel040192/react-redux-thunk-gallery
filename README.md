https://keen-narwhal-a01fec.netlify.app/

**Información destacada:**

- Un nombre que se da identifica a un reducer del que se está hablando. Por ejemplo, en src/stateGallery.js, en la variable gallerySlice, la propiedad name que tiene el valor gallery es lo que le da a un reducer llamado galleryReducer su nombre.

- La presencia de galleryReducer identifica que hay un reducer en la store de la aplicación web.

- La response que se obtiene se formatea con await response.json(), convirtiéndola en un formato utilizable, y luego se retorna.

- En el objeto extraReducers, .pending es algo que uno no crea, sino que ya está abstraído en createAsyncThunk, y determina la lógica que se utilizará cuando se espera que una llamada a una API finalice.

- En payload.action que está en el extrareducer [getPhotos.fulfilled], la payload son los datos que provienen del consumo de una API, y son hechos iguales a o son pasados al arreglo de state.photos.

- state.isLoading es establecido como false en el extrareducer [get Photos.fulfilled] porque ya no es necesario esperar a que se complete una tarea asíncrona.

**Highlighted information:**

- A name that is given identifies which reducer is being talked about. For example, in src/stateGallery.js, in the variable gallerySlice, the property name that has the value gallery is what gives a reducer called galleryReducer its name.

- The presence of galleryReducer identifies that there's a reducer in the web application's store.

- The response that is gotten back is formatted with await response.json() into a usable format, and then it's returned.

- In the extraReducers object, .pending is something that one doesn't create but it's already abstracted away in createAsyncThunk, and it determines the logic that will be used when waiting for an API call to finish. 

- In action payload that's in the extraReducer [getPhotos.fulfilled], the payload is the data that came from the API fetching, and it's made equal or passed to the array of state.photos.

- state.isLoading is set to false in the extrareducer [get Photos.fulfilled] because there's no longer the need to wait for an asynchronous task to be completed.
