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
                    onSuccess = { state ->
                        zoomState.setContentSize(state.painter.intrinsicSize)
                    },
                    contentScale = ContentScale.Crop,
                    modifier = Modifier
                        .fillMaxSize()
                )
```
