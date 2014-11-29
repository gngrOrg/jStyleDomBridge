jStyleDomBridge
===============

Bridge from [jStyleParser](http://cssbox.sourceforge.net/jstyleparser/)'s AST to [CSS DOM API](http://www.w3.org/TR/DOM-Level-2-Style/css.html).

This library is being used in [gngr](https://gngr.info) 

```

      ┌────────────┐        uses  ┌────────────┐
      │ CSS Dom    │<─────────────│ Javascript │
      │ Interfaces │              └────────────┘
      └────────────┘
             ^                               
             │                               
             │                               
             │ implements                              
             │                               
      ╔══════╧═════════╗                          
      ║     Bridge     ║
      ║ (you are here) ║
      ╚══════╤═════════╝                          
             │                               
             │ uses                          
             │                               
             │                               
             V                               
      ┌──────────────┐                        
      │ jStyleParser │                        
      │ AST          │                        
      └──────────────┘                        
```

## Contributing
Please read the [guide](https://github.com/UprootLabs/jStyleDomBridge/wiki/Contributing)

## Copyright and License

Copyright 2014 Uproot Labs India

Distributed under the [Apache v2 License](https://www.apache.org/licenses/LICENSE-2.0.html)
