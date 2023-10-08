# Things I always forget

## Angular

### How to connect module to a route

```typescript
  {
    path: '',
    loadChildren: () =>
      import(
        './modules/auth/auth.module'
      ).then((m) => m.AuthModule),
  },
```
