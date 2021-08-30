## Get list of projects
```sh
firebase projects:list
```

## Get app id. FIREBASE_APP_ID
```sh
firebase apps:list --project demoapp-6e3f3
┌──────────────────┬───────────────────────────────────────────────┬──────────┐
│ App Display Name │ App ID                                        │ Platform │
├──────────────────┼───────────────────────────────────────────────┼──────────┤
│ DemoApp  Android │ 1:1098212413682:android:146be74a8b5e5a54cd806b│ ANDROID  │
└──────────────────┴───────────────────────────────────────────────┴──────────┘
```

## Generate FIREBASE_TOKEN
```
firebase login:ci
```
