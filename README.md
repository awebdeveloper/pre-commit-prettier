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
        
        
   To use with ```tslint-eslint-rules``` include it as additional_dependencies

   To check type or if linter complaints of type (but this will slow down your commit)
   
``` 
     hooks:
        -   id: tslint
            args: ['--project','tsconfig.json','--type-check']
```

        
   
