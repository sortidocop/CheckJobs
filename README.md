# CheckJobs
Check your jenkins jobs do well.

The server CORS will be enable.

Apache server have include_module on.

And add in Apache config file:

```ruby
<IfModule mod_headers.c>
    Header set Access-Control-Allow-Origin: *
</IfModule>
</code>
```

The result is not implemented yet, the console.log result on javascript console.
