1. Always use Jetpack Compose for UI development. Never use XML layouts.
2. Use Material 3 design system and components (androidx.compose.material3.*).
3. Follow MVVM architecture with Unidirectional Data Flow (UDF).
4. Navigation must use Type-Safe Navigation Compose (2.8+) with @Serializable routes.
5. Persist Watchlist data locally using Room Database.
6. Store sensitive session tokens and TMDB API keys exclusively in EncryptedSharedPreferences.
