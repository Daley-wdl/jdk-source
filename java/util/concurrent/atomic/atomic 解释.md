### atomic 用途
- 可解决 volatile *(只保证可见性和禁止重排序)* 无法控制的原子性问题 
- 使用 AtomicReference 解决只能控制单一变量问题
- 使用 AtomicStampedReference 解决 ABA 问题