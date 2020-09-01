(APPENDIX-I) APOD API JAVASCRIPT EMBEDDING
==========================================

.. raw:: html

   <p>

var url =
"https://api.nasa.gov/planetary/apod?api\_key=NNKOjkoul8n1CH18TWA9gwngW1s1SmjESPjNoUFo";

::


    $.ajax({
      url: url,
      success: function(result){
      if("copyright" in result) {
        $("#copyright").text("Image Credits: " + result.copyright);
      }
      else {
        $("#copyright").text("Image Credits: " + "Public Domain");
      }
      
      if(result.media_type == "video") {
        $("#apod_img_id").css("display", "none"); 
        $("#apod_vid_id").attr("src", result.url);
      }
      else {
        $("#apod_vid_id").css("display", "none"); 
        $("#apod_img_id").attr("src", result.url);
      }
      $("#reqObject").text(url);
      $("#returnObject").text(JSON.stringify(result, null, 4));  
      $("#apod_explaination").text(result.explanation);
      $("#apod_title").text(result.title);
    }
    });
     <code> (APPENDIX-II) USEFUL RESOURCES </code>


    Link: https://images.nasa.gov/docs/images.nasa.gov_api_docs.pdf

