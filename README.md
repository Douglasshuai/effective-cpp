# effective-cpp
note

item2: prefer consts, enums, and inlines to #defines    
item4: make sure that objects are initialized before they're used    
item5: know what functions c++ silently writes and calls    
item6: explicitly disallow the use of compiler-generated functions you do not want    
item7: declare destructors virtual in polymorphic base classes    
item8: prevent exceptions from leaving destructors     
item9: never call virtual functions during construction or destruction    
item10: have assignment operators return a reference to *this     
item13: use objects to manage resources     
item14: think carefully about copying behavior in resource-managing classes    
item15: provide access to raw resources in resource-managing classes    
item16: use the same form in corresponding uses of new and delete    
item17: store newed objects in smart pointers in standalone statements   
item18: make interfaces easy to use correctly and hard to use incorrectly   
item19: treat class design as type design      
item21: don't try to return a reference when you must return an object   
item23: prefer non-member non-friend functions to member functions    
item24: declare non-member functions when type conversions should apply to all parameters    
item25: consider support for a non-throwing swap    
item26: postpone variable definitions as long as possible    
item27: minimize casting    
item28: avoid returning "handles" to object internals    
item29: strive for exception-safe code    
item30: understand the ins and outs of inlining     
item31: minimize compilation dependencies between files    
item32: make sure public inheritance models "is-a"    
item33: avoid hiding inherited names     
item34: differentiate between inheritance of interface and inheritance of implementation    
item35: consider alternatives to virtual functions     
item36: never redefine an inherited non-virtual function    
item37: never redefine a function's inherited default parameter value    
item38: model "has-a" or "is-implemented-in-terms-of" through composition    
item39: use private inheritance judiciously     
item40: use multiple inheritance judiciously     
item41: understand implicit interfaces and compile-time polymorphism     
item42: understand the two meanings of typename    
item43: know how to access names in templatized base classes    
item44: factor parameter-independent code out of templates    
item45: use member function templates to accept "all compatible types"    
item46: define non-member functions inside templates when type conversions are desired      
item47: use traits classes for information about types     
item48: be aware of template metaprogramming    
item49: understand the behavior of the new-handler     
item50: understand when it make sense to replate new and delete     
item51: adhere to convention when writing new and delete     
item52: write placement delete if you write placement new     
item1: distinguish between pointers and references    
item2: prefer c++-style casts    
item3: never treat arrays polymorphically    
item4: avoid gratuitous default constructors    
item5: be wary of user-defined conversion functions    
item6: distinguish between prefix and postfix forms of increment and decrement operators    
item7: never overload &&, ||, or,    
item8: understand the different meanings of new and delete    
item9: use destructors to prevent resource leaks    
item10: prevent resource leaks in constructors    
item11: prevent exceptions from leaving destructors    
item12: understand how throwing an exception differs from passing a parameter or calling a virtual function    
item13: catch exceptions by reference    
item14: use exception specifications judiciously   
item15: understand the costs of exception handling   
item16: remember the 80-20 rule   
item17: consider using lazy evaluation   
item18: amortize the cost of expected computations    
item19: understand the origin of temporary objects       
item20: facilitate the return value optimization           
item21: overload too avoid implicit type conversions        
item22: consider using op= instead of stand-alone op        
item23: consider alternative libraries      
item24: understand the costs of virtual functions, multiple inheritance, virtual base classes and RTTI      
item25: virtualizing constructors and non-member functions      
item26: limiting the number of objects of a class       
item27: requiring or prohibiting heap-based objects     
item28: smart pointers      
item29: reference counting      
item30: proxy classes       
item31: making functions virtual with respect to more than one object       
item32: program in the future tense     
item33: make non-leaf classes abstract      
item34: understand how to combine c++ and c in the same program     
item35: familiarize yourself with the language standard     
item1: choose your containers with care     
item2: beware the illusion of container-independent code        
item3: make copying cheap and correct for objects in containers     
item5: prefer range member functions to their single-element counterparts       
item6: be alert for c++'s most vexing parse     
item7: when using containers of newed pointers, remember to delete the pointers before the container is destroyed       
item8: never create conntainers of auto_ptrs        
item9: choose carefully among erasing options       
item10: be aware of allocator conventions and restrictions      
item11: understand the legitimate uses of custom allocators     
item12: have realistic expectations about the thread safety of STL containers       
item13: prefer vector and string to dynamically allocated arrays        
item14: use reserve to avoid unnecessary reallocations      
item15: be aware of variations in string implementations        
item16: know how to pass vector and string data to legacy APIs      
item17: use "the swap trick" to trim excess capacity        
item18: avoid using vector<bool>        
item19: understand the difference between equality and equivalence      
item20: specify comparison types for associative containers of pointers     
item21: always have comparison functions return false for equal values      
item22: avoid in-place key modification in set and multiset     
item23: consider replacing associative containers with sorted vectors       
item24: choose carefully between map::operator[] and map-insert when efficiency is important        
item25: familiarize yourself with the nonstandard hashed containers     
item26: prefer iterator to const iterator, reverse_iterator, and const_reverse_iterator     
item27: use distance and advance to convert a container's const_iterators to iterators      
item28: understand how to use a reverse_iterator's base iterator        
item29: consider istreambuf_iterators for character-by-character input      
item30: make sure destination ranges are big enough     
item31: know your sorting options       
item32: follow remove-like algorithms by erase if you really want to remove something       
item33: be wary of remove-like algorithms on containers of pointers     
item34: note which algorithms expect sorted ranges      
item35: implement simple case-insensitive string comparisons via mismatch or lexicographical compare        
item36: understand the proper implementation of copy_if     
item37: use accumulate or for_each to summarize ranges      
item38: design functor classes for pass-by-value        
item39: make predicates pure functions      
item40: make functor classes adaptable      
item41: understand the reasons for ptr_fun, mem_fun, and mem_fun_ref        
item42: make sure less<T> means operator<           
item43: prefer algorithm calls to hand-written loops        
item44: prefer member functions to algorithms with the same names       
item45: distinguish among count, find, binary search, lower_bound, upper_bound, and equal_range     
item46: consider function objects instead of functions as algorithm parameters      
item47: avoid producing write-only code     
item48: always #include the proper headers      
item49: learn to decipher STL-related compiler diagnostics      
item50: familiarize yourself with STL-related web sites     
item1: understand template type deduction               
item2: understand auto type deduction       
item3: understand decltype      
item4: know how to view deduced types       
item5: prefer auto to explicit type declarations        
item6: use the explicitly typed initializer idiom when auto deduces undesired types     
item7: distinguish between () and {} when creating objects      
item8: prefer nullptr to 0 and NULL     
item9: prefer alias declarations to typedefs        
item10: prefer scoped enums to unscoped enums       
item11: prefer deleted functions to private undefined ones      
item12: declare overriding functions override       
item13: prefer const_iterators to iterators     
item14: declare functions noexcept if they won't emit exceptions            
item15: use constexpr whenever possible     
item16: make const member functions thread safe     
item17: understand special member function generation       
item18: use std::unique_ptr for exclusive-ownership resource management     
item19: use std::shared_ptr for shared_ownership resource management        
item20: use std::weak_ptr for std::shared_ptr-like pointers that can dangle     
item21: prefer std::make_unique and std::make_shared to direct use of new       
item22: when using the pimpl idiom, define special member functions in the implementation file      
item23: understand std::move and std::forward       
item24: distinguish universal references from rvalue references     
item25: use std::move on rvalue references, std::forward on universal references        
item26: avoid overloading on universal references       
item27: familiarize yourself with alternatives to overloading on universal references       
item28: understand reference collapsing     
item29: assume that move operations are not present, not cheap, and not used        
item30: familiarize yourself with prefect forwarding failure cases      
item31: avoid default capture modes     
item32: use init capture to move objects into closures      
item33: use decltype on auto&& parameters to std::forward them      
item34: prefer lambdas to std::bind     
item35: prefer task-based programming to thread-based       
item36: specify std::launch::async if asynchronicity is essential       
item37: make std::threads unjoinable on all paths       
item38: be aware of varying thread handle destructor behavior       
item39: consider void futures for one-shot event communication      
item40: use std::atomic for concurrency, volatile for special memory        
item41: consider pass by value for copyable parameters that are cheap to move and always copied     
item42: consider emplacement instead of insertion       
