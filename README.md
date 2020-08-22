# emailsend

Here is a quick form to send an email. You have some flexibility to make changes. 

There are changes with the image_picker api. You will need to make some changes in the future. 

This is old api. 
File image = await ImagePicker.pickImage(...)	

This is the new api.
PickedFile image = await _picker.getImage(...)

More details on https://pub.dev/packages/image_picker
