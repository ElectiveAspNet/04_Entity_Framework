<pre>

{
  "version": "1.0.0-*",
  "buildOptions": {
    "debugType": "portable",
    "emitEntryPoint": true, 
    "preserveCompilationContext": true
  },
  "dependencies": {},
  "frameworks": {
    "netcoreapp1.1": {
      "dependencies": {
        "Microsoft.NETCore.App": {
          "type": "platform",
          "version": "1.1.0"
        }, 
        "Microsoft.AspNetCore.Server.Kestrel" : "1.1.0",
        "Microsoft.AspNetCore.Mvc": "1.1.0",
        <b>"Microsoft.EntityFrameworkCore.Sqlite": "1.0.0",
        "Microsoft.EntityFrameworkCore.Tools": {
          "version": "1.0.0-preview4-final",
          "type": "build"
    }</b>
      },
      "imports": "dnxcore50"
    }
  }, <b>
  "tools": {
    "Microsoft.EntityFrameworkCore.Tools": "1.0.0-preview4-final"
  } </b>
}


</pre>