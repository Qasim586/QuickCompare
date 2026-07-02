# delivery-compare-dubai

React Native (Expo + TypeScript) app for comparing 10-15 minute delivery options in Dubai across Noon Minutes, Talabat Mart, and Careem Quik.

## What it does

- Compares product offers by speed, deal, and price
- Suggests the fastest available option
- Highlights best discount and lowest price
- Shows product availability by platform

## Tech stack

- Expo + React Native + TypeScript
- React Navigation (native stack + bottom tabs)
- Zustand for app state
- Axios for API client placeholders

## Project structure

- src/screens: Home, ProductDetails, Deals, Availability
- src/components: reusable comparison card
- src/navigation: stack/tab setup
- src/store: state store
- src/types: domain models
- src/data: mock service/product data
- src/utils: comparison/ranking engine
- src/services: API client placeholders

## Environment setup

1. Copy `.env.example` to `.env`
2. Replace placeholder API values

## Run

- npm install
- npm start
- npm run android
- npm run ios
- npm run web

## Current data source

The app currently uses mock data for:

- Noon Minutes
- Talabat Mart
- Careem Quik

## Next integration steps

1. Add real product/feed ingestion for each platform.
2. Normalize item names/units and map equivalent products.
3. Populate delivery ETA and deal signals from live sources.
4. Add location-based availability and fee logic.
5. Add caching and refresh intervals for near real-time updates.
