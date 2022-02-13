# Vue-Studies

## Steps to execute the tests in the **updateDOMVue2**

> Open the **.html** file in the browser
>
> At the browser terminal and execute the commands below:
>> <code>info.reactive_msg = 'okay'</code>
>>
>> The innerText of the **H1** tag will be updated and the new value will be assigned to the **msg** property.
>> It means that the innerText of the **H1** tag is sync with the **msg** property.

## Steps to execute the tests in the **updateDOMVue3**

> Open the **.html** file in the browser
>
> At the browser terminal the commands below:
>> <code>info_proxy.msg</code>
>> 
>> **RETURN**: send me to the H1 tag returned by proxy getter!
>> 
>> <code>info_proxy.msg = 'okay'</code>
>> 
>> **RETURN**: okay returned by proxy setter
>> 
>>>> The innerText of the **H1** tag will be updated and the new value will be assigned to the **msg** property.
>> It means that the innerText of the **H1** tag is sync with the **msg** property.
>> 
>> <code>info_proxy.num</code>
>> 
>> **RETURN**: 10
>> 
>> <code>info_proxy.num++</code>
>> 
>> **RETURN**: 11

## Steps to execute the tests in the **singletonAndFactory**

> Open the **.html** file in the browser
>
> At the browser terminal the commands below:

### Singleton Pattern

>> <code>instance_aS</code>
>> 
>> **RETURN**: <code>{ city: "London" }</code>
>> 
>> <code>instance_bS</code>
>> 
>> **RETURN**: <code>{ city: "London" }</code>
>> 
>> <code>info</code>
>> 
>> **RETURN**: <code>{ city: "London" }</code>

>> Settin a new value to the city name:
>> 
>> <code>instance_bS.city = 'okay'</code>

>> Checking the values:
>> 
>> <code>instance_aS</code>
>> 
>> **RETURN**: <code>{ city: "okay" }</code>
>> 
>> <code>instance_bS</code>
>> 
>> **RETURN**: <code>{ city: "okay" }</code>
>> 
>> <code>info</code>
>> 
>> **RETURN**: <code>{ city: "okay" }</code>



### Factory Pattern

>> <code>instance_aF</code>
>> 
>> **RETURN**: <code>{ city: "London" }</code>
>> 
>> <code>instance_bF</code>
>> 
>> **RETURN**: <code>{ city: "London" }</code>

>> Settin a new value to the city name:
>> 
>> <code>instance_bF.city = 'okay'</code>

>> Checking the values:
>> 
>> <code>instance_aF</code>
>> 
>> **RETURN**: <code>{ city: "London" }</code>
>> 
>> <code>instance_bF</code>
>> 
>> **RETURN**: <code>{ city: "okay" }</code>

