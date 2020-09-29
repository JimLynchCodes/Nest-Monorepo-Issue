# Nest-Monorepo-Issue

Created from scratch with these commands:

```
nest new  (and named it "my-app")
```

```
nest g app (and named it "my-msvc-1")
```

```
nest g app (and named it "my-msvc-2")
```

```
nest g lib  (and named it "my-lib")
```

Changed the service of my-msvc-1 to return "foo" rather than "Hello World!"


Then _try_ to run the my-msvc-1 service:

(navigate into "monorepo" folder)
```
nest start my-msvc-1
```


## Notice how ONLY the code in "main" is being run and NOT the code from my-msvc-1 project 

😥

