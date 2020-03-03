```
method

function
func
fun
```



```
public function index()
{
	return view('projects.index', [
		'projects' => auth()->user()->projects
	]);
}
```

###### public, {}, ;
```
function index()
	= view('projects.index', [
		'projects' => auth()->user()->projects
	])
```

###### function -> fun
```
fun index()
	= view('projects.index', 
		['projects' => auth()->user()->projects])
```

###### => ( is return )
```
fun index =>
	view: 'projects.index',
		['projects' => auth()->user()->projects]
```



###### i don't thing so.
```
fun index
> view
> data
:
stuffe
;
```

###### just be a function, not need to be anything
```
fun index;
```

###### different kind of function
```
function index():void {}

function index() -> void {}

void index() {}
```