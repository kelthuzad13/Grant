# Grant

forked from [Grant](https://github.com/anthonycr/Grant)

- Add permission type that user denied and chose never ask again.
- In fragment, request permission from getActivity() to avoid the [nested fragment problem](http://stackoverflow.com/questions/33169455/onrequestpermissionsresult-not-being-called-in-dialog-fragment/35268661). 

## TODO 
 
- Use fragment to request permission and get callback.
- In some custom ROM under Android 6.0, it is still use new permission request model. We should handle these situations. 

## License
```
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
