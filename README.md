# Custom Wrap Layout for Xamarin Forms

Since Xamarin Forms doesn't support native GridView , I found [this Gist](https://gist.github.com/NicoVermeir/7ffb34ebd639ed958382) and made some modifications.

# Main Features

- MVVM compatible with bindable ItemsSource and SelectedItem.
- Supports both Vertical & Horizontal orientations.

# Known Issues

- No ScrollViewever support yet.You need to insert the control inside of ScrollViewer in order to scroll through.
- No SelectionMode support yet and SelectedItem works as tapped item.