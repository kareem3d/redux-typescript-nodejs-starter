Typescript, React, Redux, Nodejs, Mongodb starter project
---------------------------------------------------------

# Workflow for creating a new resource

## :file_folder: Shared
- Add api interface to src/shared/api.d.ts
- Add model interface to src/shared/models.d.ts

## :file_folder: Server 
##### :heavy_check_mark: Model
- Create configureMethod to create db model
- Add it to models.config.ts
- Create Repository class
	
##### :heavy_check_mark: Controller
- Create a controller class that implements the interface you added in api.d.ts
- add it to the kernel.config.ts

##### :heavy_check_mark: Router
- Create the resource router
- add it to the router.config.ts

## :file_folder: Client
##### :heavy_check_mark: Api
- Create Api class that implements the api interface you added in api.d.ts
	
##### :heavy_check_mark: Constants
- Add resource actions constants

##### :heavy_check_mark: Actions
- Create action creators
- Add them to kernel.config.ts

##### :heavy_check_mark: Reducers
- Create reducers to manage the state
