# Winglang Experiments

### Wingpresso from Dev Agrawal

- create an API Gateway with routes to add a coffee order, get it and update it (equivalent to javascript node express routes but deployed to the cloud)
- [youtube](https://www.youtube.com/watch?v=lLiBUKcpSug&t=1169s)
- [code](./wingpresso/wingpresso.w)
  ![wingpresso_ss](./wingpresso/wingpresso_ss.png)

### Winglang Update: Multi-file Support with Elad and Chris

- [youtube](https://www.youtube.com/watch?v=WAnM4ZUbLnE)
- code [main](./features/multifile/main.w) [store](./features/multifile/store.w)
  ![wing_multifile_support](./features/multifile/wing_multi_file_support.png)

## Features

### Javascript Support

- Notes: I was unable to both 'extern' (import) javascript into wing and 'bring' (import) wing into wing. But the javascript interop via import works with a static function of a class.
- [code](./features/javascript/javascript.w)
  ![wing_javascript_support](./features/javascript/wing_javascript_support.png)
