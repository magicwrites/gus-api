# Quickstart

## Installation

```bash
npm install @magicwrites/gus-api
```

## Example usage

```javascript
import { GusApiRegon } from '@magicwrites/gus-api';

const service = new GusApiRegon('YOUR_API_KEY');

const results = await service.search({
  Nip: '1234567890',
});

console.log('Results', results);
```

## Search params

| Name       | Example                       | Optional |
| ---------- | ----------------------------- | -------- | --- |
| Nip        | 9471986146                    | true     |
| Krs        | 0000090577                    | true     |
| Regon      | 008376680 or 00000008376680   | true     |
| Krsy       | 0000090577,0000090577         | true     |
| Nipy       | 9471986146,9471986146         | true     |
| Regony14zn | 00000008376680,00000008376680 | true     |
| Regony9zn  | 008376680,008376680           | true     |     |
