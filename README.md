# My-Learnings

## Placeholder for images

Image placeholder with text, custom font, size etc

https://placehold.co/

eg:

```Kotlin
AsyncImage(
    model = ImageRequest.Builder(LocalContext.current)
        .data(url)
        .crossfade(true)
        .build(),
    placeholder = painterResource(R.drawable.image_loading_placeholder),
    error = painterResource(R.drawable.image_error_placeholder),
    contentDescription = stringResource(R.string.description),
    contentScale = ContentScale.Crop,
    modifier = Modifier
        .fillMaxSize()
)
```

image_loading_placeholder

![image_loading_placeholder](https://github.com/dipinpj/My-Learnings/assets/49065133/9dad7152-e114-4571-a390-448980df9e0a)


image_error_placeholder

![image_error_placeholder](https://github.com/dipinpj/My-Learnings/assets/49065133/093eefe2-d066-4791-9d30-fe2bfb1f9422)
