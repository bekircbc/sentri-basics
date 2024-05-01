# Sentry

- Create a sentry account
- Create a new project and select appropriate platform
- Install Sentry SDK
- Initialize Sentry in your App
- Capture Error
- Customize Configuration
- Test
- Monitor Sentry Dashboard

## Install Sentry SDK

      npm install @sentry/browser

## Initialize Sentry in Your Application

      import * as Sentry from '@sentry/browser';

      Sentry.init({
        dsn: 'YOUR_SENTRY_DSN'
      });

## Capture Errors

      try {
      
      } catch (error) {
        Sentry.captureException(error);
      }

## Read More

- [Click hier to read](https://develop.sentry.dev/)

      
