# USART (Universal Synchronous and Asynchronous Receiver-Transmitter)

## Summary

- Includes

```
#include "usart.ceu"                                            // must always be included
```

- Code Abstractions

```
code/await Usart    (var int bps)                   -> NEVER    // enables USART
code/await Usart_TX (var&[] byte buf)               -> none     // transmits buffer
code/await Usart_RX (var&[] byte buf, var usize? n) -> none     // receives at least n bytes into buffer
```

## Introduction

`TODO`
