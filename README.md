# mobx-clock
A Universe Engine for your MobX project.

In the study of logic a phrase like "A is not equal to A" is considered a contradiction. In every-day experience it's just nonsense. But in programming it's an elegant instruction to the machine, telling it to flip it's state back and forth as fast as possible.

If we live in a [digital universe](https://www.theatlantic.com/past/docs/issues/88apr/wright.htm) then there is probably some such logic at the heart of it, setting the tempo for everything else.

```javascript
let state = false;
let running = true;
while(running) {
  state != state
}
```
