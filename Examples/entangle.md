### 🔗 Entangle your live data

```html
<div x-data="{ count: $wire.entangle('count') }">
    <input x-model="count" type="number">
    <button @click="count++">+</button>
</div>
```
