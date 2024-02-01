# fsd-react-snippets

Сниппеты для React и cva

## Сниппеты

- ccva
```typescript
const cva$1 = cva([
  '${TM_FILENAME_BASE}-cva$1',
  '$2',
]);
```

- dc
```tsx
import { FC } from 'react';
import { cva } from 'class-variance-authority';

interface Props {
  
}

const cvaRoot = cva(['${TM_FILENAME_BASE}-cvaRoot', '']);

const ${TM_FILENAME_BASE}: FC<Props> = () => {
  return (
    <div className={cvaRoot()}>,
      {$1}
    </div>
  )
}

export default ${TM_FILENAME_BASE}
```


**Enjoy!**
