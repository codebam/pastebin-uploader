<div id="container">
<h1>Sean's Pastebin</h1>
<p>After uploading you will be redirected to yourfile.txt. Make sure to
save the link if you're encrypting. You can change .txt to any valid MIME
type to display it in the browser.</p>
<h2>plain text</h2>
<form method="post" enctype="multipart/form-data">
<div>
<textarea name="paste" rows="20" cols="30" id="paste"></textarea>
</div>
<button>submit</button>
<h2>plain file</h2>
</form>
<form method="post" enctype="multipart/form-data">
<div>
<input type="file" id="upload" name="upload">
</div>
<button>submit</button>
</form>
<h2>encrypted text</h2>
<form method="post" action="./encrypt" enctype="multipart/form-data">
<div>
<textarea name="paste" rows="20" cols="30" id="paste"></textarea>
</div>
<button>submit</button>
</form>
<h2>encrypted file</h2>
<form method="post" action="./encrypt" enctype="multipart/form-data">
<div>
<input type="file" id="upload" name="upload">
</div>
<button>submit</button>
</form>
</div>
