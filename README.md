# jquery-bootstrap-autocomplete.css
jQuery UI Autocomplete Bootstrap 3 Style

![Demo](https://raw.githubusercontent.com/PeterQuistgaard/jquery-bootstrap-autocomplete.css/master/autocomplete.png)




```html

<!doctype html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>jQuery UI Autocomplete</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" />
    <link rel="stylesheet" href="lib/jquery-ui/themes/base/menu.css" />
    <link rel="stylesheet" href="lib/jquery-ui/themes/base/autocomplete.css" />
    
    <link href="css/jquery-bootstrap-autocomplete.css" rel="stylesheet" />
    
</head>
<body>
    <div class="container">
        <div class="row">
            <div class="col-md-6">
                <h1>Demo: Autocomplete <small>with Bootstrap style </small> </h1>
                <div>
                    <label for="tags">Tags: </label>
                    <input id="tags" class="form-control">
                </div>
            </div>
        </div>
    </div>
    <script src="https://code.jquery.com/jquery-1.12.4.js"></script>
    <script src="https://code.jquery.com/ui/1.12.0/jquery-ui.js"></script>
    <script>
          $( function() {
            var availableTags = [
              "ActionScript",
              "AppleScript",
              "Asp",
              "BASIC",
              "C",
              "C++",
              "Clojure",
              "COBOL",
              "ColdFusion",
              "Erlang",
              "Fortran",
              "Groovy",
              "Haskell",
              "Java",
              "JavaScript",
              "Lisp",
              "Perl",
              "PHP",
              "Python",
              "Ruby",
              "Scala",
              "Scheme"
            ];
            $( "#tags" ).autocomplete({
              source: availableTags
            });
          });
    </script>
</body>
</html>

```
