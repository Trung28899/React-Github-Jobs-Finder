I. Tools Used: 

    Github jobs API: 
    https://jobs.github.com/api

    $ npm install axios react-bootstrap
    have to paste this in public/index.html for bootstrap to 
    be applied: 
    <link
      rel="stylesheet"
      href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css"
      integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk"
      crossorigin="anonymous"
    />

    https://cors-anywhere.herokuapp.com/ for CORS issue
    added before api url (base url)

    axios in useFetchJobs cancel to cancel any previous request 
    that are not applicable anymore

    $ npm install react-markdown