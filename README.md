# Advanced Custom Icon Set Cleanup

Using [CustomIconLoader](https://github.com/iconify/iconify/blob/main/packages/utils/src/loader/types.ts#L17) to fix building and applying optimizations per icon request in [ @iconify/tools/@iconify-demo/unocss](https://github.com/iconify/tools/tree/main/%40iconify-demo/unocss) example.

UnoCSS Icon Loader is designed to handle pre-built [IconifyJSON]() collections without customizations. It is possible to use it with custom collections, but it requires the work here to delay resolving the icon until the collection is ready. On heavy collections/customizations process you may suffer some performance bottlenecks. 
