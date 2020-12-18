# phaser3_memory_leak_test

Just test the same URL of the picture added 1000 times (diff `key`)
-> then textures.remove(key) `for loop remove all keys`
-> then switch to next scene
-> the memory no release (memory usage from 40MB to 464MB).

![Task Manager](./assets/task-manager.png)
