# Metro City Help Center

## 1. Summary
This project simulates a help center system using stacks and queues.  
It focuses on implementing LIFO (stack) and FIFO (queue) behaviors using Python data structures.

---

## 2. Complexity

- **ActionStack.pop** → O(1)  
  Removing the last element from a list takes constant time.

- **RequestQueue.dequeue** → O(1)  
  deque.popleft() removes from the front in constant time.

- **is_note_balanced** → O(n)  
  We loop through each character once.

- **process_request_line** → O(n)  
  Each citizen is processed exactly once.

---

## 3. Edge-case checklist

- **Empty action stack**  
  pop() and peek() return None safely.

- **Empty request queue**  
  dequeue() and peek() return None safely.

- **Empty string in is_note_balanced**  
  Returns True (nothing to match).

- **No brackets in note**  
  Returns True.

- **Empty citizen list**  
  Returns an empty list.

---

## 4. Assistance & Sources

- AI used: Yes  
- Helped with: Understanding stack/queue implementation and test structure  
- Sources: Course materials and Python documentation