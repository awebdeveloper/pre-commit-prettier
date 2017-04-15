Tslint for pre-commit
========================

Tslint package for pre-commit>=0.12.0.

For pre-commit: see https://github.com/pre-commit/pre-commit

For Tslint: see https://github.com/palantir/tslint


### Using Tslint with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: git://github.com/awebdeveloper/pre-commit-tslint/
        sha: ''  # Use the sha or tag you want to point at
        hooks:
        -   id: tslint
        
        
   To use with ```tslint-eslint-rules```
   
``` 
     hooks:
        -   id: tslint
            additional_dependencies: ['tslint-eslint-rules@1.5.0']
```

   To check type or if linter complaints of type 
   
``` 
     hooks:
        -   id: tslint
            args: ['--program path/to/tsconfig.json','--type-check']
```

        
   
