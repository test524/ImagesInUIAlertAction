# AlertViewController

Adds ability to display `UIImage` above the title label of `UIAlertController`.
Functionality is achieved by adding “\n” characters to `title`, to make space
for `UIImageView` to be added to `UIAlertController.view`. Set `title` as
normal but when retrieving value use `originalTitle` property.

# UIAlertAction+Extensions

Adds ability to display image left of the action title, by leveraging KVC.
Also checks whether `UIAlertAction` responds to appropriate selector to
avoid crashes if property is not available in the future.



