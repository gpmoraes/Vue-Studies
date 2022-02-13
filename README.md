# Vue-Studies

## Steps to execute the tests in the **UpdateDOMVue2**

> Open the **.html** file in the browser
>
> At the browser terminal and execute the commands below:
>> <code>info.reactive_msg = 'okay'</code>
>>
>> The innerText of the **H1** tag will be updated and the new value will be assigned to the **msg** property.
>> It means that the innerText of the **H1** tag is sync with the **msg** property.

## Steps to execute the tests in the **UpdateDOMVue3**

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
