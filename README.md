# MarketApp

C# / .NET 8 Windows Forms market application, with SQL Server database scripts, repositories, services, DTOs and tests.

## Open the project

Open `G11_Market/G11_Market.sln` in Visual Studio with .NET 8, Windows desktop development and SQL Server database project support installed.

Database definitions and stored procedures are in `G11_Market/Market.Database`. Configure your local database connection in the app and test appsettings files. Integration tests require a dedicated test database and may modify its contents.

## JWT configuration

Before using token generation or validation, set the `MARKET_JWT_KEY` environment variable to your own cryptographically random secret of at least 32 characters. Do not commit this value. Restart Visual Studio after changing environment variables.

The hardcoded signing key from the local source was removed from this publication copy. Replace it in any existing deployment that used it.

## Contents

The source includes the application, database project, DTOs, extensions, repositories, services and tests. Generated build output, IDE caches and local tool state are excluded.
