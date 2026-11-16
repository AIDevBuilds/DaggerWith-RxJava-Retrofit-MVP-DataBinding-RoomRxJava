# Dagger with RxJava, Retrofit, MVP, Data Binding and Room (Android)

The most complete of the Dagger samples: it adds a Room database next to the Retrofit posts API.

This is an older sample kept for reference. It is not actively maintained.

## What it shows

- `data/network`: the `PostApi` and the `Post` model, loaded from [JSONPlaceholder](https://jsonplaceholder.typicode.com)
- `data/db`: `AppDatabase`, a `User` entity and its `UserDao` (Room 1.1.0)
- `di`: Dagger components (`FragmentComponent`, `PresenterComponent`), modules (`AppModule`, `FragmentModule`,
  `NetworkModule`) and scopes
- MVP with Data Binding on top

## Stack

Java, Dagger 2.14.1, RxJava 2.1.9, Retrofit 2.3.0, Room 1.1.0, Data Binding compiler 3.1.2,
`minSdkVersion 16`, `compileSdkVersion 27`.

## Run

Open the project in Android Studio and run the `app` module. It uses an older Android Gradle plugin (3.1.x) and `compileSdkVersion 27`, so Android Studio may ask you to update the Gradle wrapper and plugin.

## License

MIT. See [LICENSE](LICENSE).
