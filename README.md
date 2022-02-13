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
>> **Return**
>> <code>"send me to the H1 tag returned by proxy getter!"</code>
>> 
>> <code>info_proxy.msg = 'okay'</code>
>> **Return**
>> <code>"okay returned by proxy setter"</code>
>> The innerText of the **H1** tag will be updated and the new value will be assigned to the **msg** property.
>> It means that the innerText of the **H1** tag is sync with the **msg** property.
>> 
>> 
>> <code>info_proxy.num</code>
>> **Return**
>> <code>"10"</code>
>> 
>> <code>info_proxy.num++</code>
>> **Return**
>> <code>"11"</code>
