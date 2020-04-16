# C++

* [ ] Move async_hooks-related methods from Environment to AsyncHooks.

  ```cpp
  // The necessary API for async_hooks.
  inline double new_async_id();
  inline double execution_async_id();
  inline double trigger_async_id();
  inline double get_default_trigger_async_id();
  ```
