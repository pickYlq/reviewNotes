# C/S结构及B/S结构定义与区别

## 定义

* C/S架构，即客户机/服务器架构，它是软件系统体系结构。通过它，可以充分利用两端硬件环境的优势，能把任务合理分配到客户端和服务端，降低了系统的通讯开销。

* B/S架构，即浏览器/服务器架构，它是软件系统体系结构。这种模式统一了客户端，将系统功能实现的核心部分集中到服务器上，简化了系统的开发、维护和使用。
  
## 优缺点

### C/S

* 客户端和服务端的软件都需要程序员进行编写

* 客户端需要单独安装和调试，维护起来麻烦

* 可以将一部分计算分离到客户端上，减少服务端的压力。

* 开发相对比较复杂，比如要自定义协议，需要自己开发客户端与服务器端的通讯处理模块。

### B/S

* 客户端不需要程序员编写，直接使用浏览器

* 只需要维护服务器，维护简单

* 所有运算都在服务器端，相对压力较大

* 开发相对简单(因为c/s架构需要自定义协议，开发相应的通信模块，而b/s使用标准化的http协议，浏览器与web服务器都提供了相应的通信模块)。