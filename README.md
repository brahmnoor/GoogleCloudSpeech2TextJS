## Google Cloud API Speech to Text using pure client side Javascript
This project was built for Teli at The University of Hong Kong. This uses Google Cloud Speech APIs to convert speech to text, unlike other counterparts - this is done entierly on the client side.

### How to Use
- Check it out [here](http://brahmnoor.me/GoogleCloudSpeech2TextJS/ "here") (note, the access token is not uploaded, hence the speech to text won't happen yet)
- Edit the file `create_access_token.js` on line 19 to set the access token of your Google API account.
- Run `index.html`.


### Production Tips
- This is not production ready because it might mean exposing your API keys, so handle that carefully before deployment.
- Another version of this using Express and Socket (for real time speech to text conversion) was made [here](https://github.com/brahmnoor/TextToSpeech "here"). 
