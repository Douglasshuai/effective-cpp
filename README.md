# effective-cpp
note

item2: prefer consts, enums, and inlines to #defines    
item3: use const whenever possible    
item4: make sure that objects are initialized before    
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
item20: prefer pass-by-reference-to-const to pass-by-value    
item21: don't try to return a reference when you must return an object   
item22: declare data members private    
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


