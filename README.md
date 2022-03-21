<!DOCTYPE html>
<html>
<head>
  <title>Youtube Videos Download Script code - nicesnippets.com</title>
  <link rel="stylesheet" type="text/css" href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/5.0.0-alpha1/css/bootstrap.min.css">
  <script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/5.0.0-alpha1/js/bootstrap.min.js"></script>
</head>
<body class="bg-dark">
  <div class="col-md-6 offset-md-3 mt-5">
    <div class="card">
      <div class="card-header bg-info">
        <h5>Youtube Videos Download Any Online Videos - nicesnippets.com</h5>
      </div>
      <div class="card-body">
        <div class="row">
          <div class="col-md-12">
            <div class="form-group">
              <label class="text-weight"><b>Online Videos Link:</b></label>
              <input type="txt" name="link" class="form-control link" required>
            </div>
          </div>
        </div>
        <form class="form-download">
          <div class="row">
            <div class="col-md-12">
              <div class="form-group">
                <label class="text-weight"><b>Select Video Fromate:</b></label>
                <select class="form-control formte" required>
                  <option selected disabled>Select Video Formate</option>
                  <option value="mp3">Mp3</option>
                  <option value="mp4a">144 Mp4</option>
                  <option value="360">360 Mp4</option>
                  <option value="480">480 Mp4</option>
                  <option value="720">720 Mp4</option>
                  <option value="1080">1080 Mp4</option>
                  <option value="4k">4k Mp4</option>
                  <option value="8k">8k Mp4</option>
                </select>
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col-md-12">
              <div class="form-group mt-4 download-video">
                <button class="btn btn-success btn-block click-btn-down" type="submit">Click Me</button>
              </div>
            </div>
          </div>
        </form>
      </div>
    </div>
  </div>
</body>
<script type="text/javascript">
  $(".click-btn-down").click(function(){
      var link = $(".link").val();
    var fromate = $(".formte").children("option:selected").val();
    var src =""+link+"="+fromate+"";
    downloadVideo(link,fromate);
  });
  function downloadVideo(link,fromate) {
      $('.download-video').html('<iframe style="width:100%;height:60px;border:0;overflow:hidden;" scrolling="no" src="https://loader.to/api/button/?url='+link+'&f='+fromate+'"></iframe>');
  }
</script>
</html>
