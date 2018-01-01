# photo-renamer
Use Java to create an interface to allow users to add new tags to the name of photo files from a certain directory.
Users select a folder which contains image files with the common extensions (.jpeg, .png, etc.) and can go through these images
and rename them based on a tag list. A master tag list is loaded into the program upon every use and is saved as a serializable
file which keeps the list of tags a user can add to an image's name. (Tags take the form: @tag_name). The interface also allows
users to remove tags from the image and delete tags from the master list. Users can then confirm the changes they've made and 
thus successfully rename an image. A log is available to view previous names of images and revert back to an older name.
