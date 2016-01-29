### GKImagePicker

Thanks to @gekitz who make this amazing [control](https://github.com/gekitz/GKImagePicker). I only added the feature to make the image scale to fit in screen and fixed some bugs.

Ever wanted a custom crop area for the UIImagePickerController? Now you can have it with _GKImagePicker_. Just set your custom crop area and that's it. Just 4 lines of code. If you don't set it, it uses the same crop area as the default UIImagePickerController.

### How to use it

- just drag and drop the files in under "GKClasses" & "GKImages" into your project.
- look at the sample code below.
- this project contains a sample project as well, just have a look at the implementation of `ViewController.m` 
- have fun and follow [@gekitz](http://www.twitter.com/gekitz).


### Sample Code
	
	self.imagePicker = [[GKImagePicker alloc] init];
    self.imagePicker.cropSize = CGSizeMake(320, 90);
    self.imagePicker.delegate = self;
    
     [self presentModalViewController:self.imagePicker.imagePickerController animated:YES];
     

### License
Under MIT. See license file for details.



    