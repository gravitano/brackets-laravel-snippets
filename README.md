brackets-laravel-snippets
===

Laravel 4.1 snippets for the `Brackets Snippets` Brackets extension

---

## Install

Install [Brackets](http://brackets.io/)

Install [Brackets Snippets](https://github.com/jrowny/brackets-snippets) *( 'File > Extension Manager' )*

Navigate to `~/Library/Application Support/Brackets/extensions/user/jrowny.brackets.snippets/`

1. Add the following json files to `data/`
    * `laravel.forms.json`
2. Add the `laravel/` directory to `data/snippets/`
3. Reload Brackets with extensions: `cmd + r`

---

## Usages

##### Forms
    l:form:route 
        {{ Form::open(array('route' => '...')) }}
        {{ Form::close() }}
 
    l:form:text
    	{{ Form::text('', Input::old(''), array('placeholder' => '')) }}
        
        
## Notes
I'm building this as need for snippets arises, so this will take a while to flush out.