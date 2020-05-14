# KerasFlaskApi

tensorflow.python.framework.errors_impl.FailedPreconditionError: Error while reading resource variable dense_1/bias from Container: localhost. This could mean that the variable was uninitialized. Not found: Container localhost does not exist. (Could not find resource: localhost/dense_1/bias)
	 [[{{node dense_1/BiasAdd/ReadVariableOp}}]]
   
    prøver at fikse ^ error
    
    Tror det har noget at gøre med tråde og async, måske skal det settes sessions eller noget lign. 
