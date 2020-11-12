# General Naming Conventions

## Variables & Constants

### Booleans

| What | Rule | Example |
| ---- | ---- | ------- |
| booleans singular | (is\|has)[Noun singular] | isActive, areActive |
| booleans plural   | (are\|have)[Noun plural] | hasFreeItem, haveDiscounts |

## Testing

| What | Rule | Example |
| ---- | ---- | ------- |
| spies | [code being spied]Spy | fetchSpy |
| mocks | [code being mocked]Mock | fetchMock |

## Filenames

| What | Rule | Example |
| ---- | ---- | ------- |
| React Component | [ComponentName].(jsx|tsx) | Avatar.jsx, NavMenu.tsx |
| Selectors | [modulename].selectors.(js|ts) | cart.selectors.js|
| Redux Reducer | [moduleName].reducer.(js|ts) | cart.reducer.js |
