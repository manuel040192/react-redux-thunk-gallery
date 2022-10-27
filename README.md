https://keen-narwhal-a01fec.netlify.app/

- The name that is given identifies which reducer is being talked about. For example, the property name that has the value gallery has a reducer called galleryReducer.

- The presence of galleryReducer identifies that there's a reducer in store.

- The response that is gotten back is formatted with await response.json() into a usable format, and then it's returned.

- In the extraReducers object, .pending is something that one doesn't create but it's already abstracted away in createAsyncThunk, and it determines the logic that will be used when waiting for an API call to finish. 
