# Fund Filter Project

## Project Specification
Build a .net mvc application to filter securities returned from the following API

  https://www.fundslibrary.co.uk/FundsLibrary.DataApi.Web
  https://www.fundslibrary.co.uk/FundsLibrary.DataApi.Web/Documentation/Examples?api=Securities

## Expectations

- The list should be paged

- The filter should allow filtering by at least 2 elements

- The filtering button should use javascript to access the list via ajax - no page reload

- The api layer should be encapsulated in its own repository in a separate assembly dll (preferably .net standard) (should include unit tests)

- Inject this dependency using Castle Windsor


Extra bonus! allow for a basic ‘email me this fund suggestion’ button (SMTP server determined by web config)
