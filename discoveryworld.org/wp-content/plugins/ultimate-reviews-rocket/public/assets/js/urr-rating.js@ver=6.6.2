jQuery(document).ready(function() {
	jQuery.fn.rating = function(options) {
		var self = this;
		var settings = jQuery.extend({
		color: "#556b2f",
		max_stars : 5 ,
		clearSelected : function() {
			jQuery('.plugin-rating i').each(function() {
			jQuery(this).addClass('fa-star-o').removeClass('fa-star');
		});
	},
	setRating : function()
		{
		if(self.val())
		{
			var position = parseInt(self.val())-1;
			// alert(position+1);
			for(var i=0;i<=position;i++)
			{
				//jQuery(".plugin-rating i").addClass("fa-star").removeClass("fa-star-o");

			}
		}   
		}

	}, options );
		var ratingHtml ='<div class="plugin-rating rating"><i class="fa fa-star-o" id="1" aria-hidden="true" data-toggle="urr-rate1" title="Poor"></i><i class="fa fa-star-o" id="2" aria-hidden="true" data-toggle="urr-rate2" title="Not Good"></i><i class="fa fa-star-o" id="3" aria-hidden="true" data-toggle="urr-rate3" title="Average"></i><i class="fa fa-star-o" id="4" aria-hidden="true" data-toggle="urr-rate4" title="Good"></i><i class="fa fa-star-o" id="5" aria-hidden="true" data-toggle="urr-rate5" title="Excellent"></i></div>';
	self.filter('input').each(function(){
		jQuery(self).after(ratingHtml);
		jQuery(self).hide();
	});
	
	settings.setRating(); 
	jQuery(document).on('click','.plugin-rating i',function(){
		var position = jQuery(".plugin-rating i").index(this);
		self.val(position+1); 
		settings.setRating();    	
		var current_rating_value = jQuery('#rating_set_value').val();
		var current_rating_URL = jQuery('#rating_set_url').val();
		var selected_star = position+1;
		if(typeof(selected_star) != 'undefined'){
			if(selected_star < current_rating_value) {
				console.log(selected_star);
				window.location.href = current_rating_URL+"/your-feedback?urr_rating_value="+selected_star;
			} else {
				window.location.href = current_rating_URL+"/social-media-reviews?urr_rating_value="+selected_star;
			}
		}else{
			alert('choose your Threshold Rating');
		}
	});
        

	jQuery(document).on('mouseenter','.plugin-rating i.fa',function(){
		var getId = jQuery(this).attr('id');
		jQuery( "i.fa" ).each(function() {
			if(jQuery(this).attr('id')<=getId)
			{
				
				jQuery('.plugin-rating i#'+jQuery(this).attr('id')).addClass('fa-star').removeClass('fa-star-o');
			}
		});
		
	});

        jQuery(document).on('mouseout','.plugin-rating i',function(){
        	settings.clearSelected();
        	settings.setRating();
        });        
        
        return self;
    };
    
    
    jQuery('#ratingme').rating();
});

jQuery(document).ready(function() {
	jQuery(document).on('click','.urr-plugin-admin-submit-btn',function(){
	var error_flag=true;
	var name_length = jQuery('#urr_user_name').val().trim().length;
	if(name_length<1){
		jQuery(".urr-name-error-span").remove();
		jQuery('.urr-Uname-div').append('<span class="urr-name-error-span" style="color: #ff0000;"><br/>This field can not be empty</span>');
		error_flag= false;
	}
	else{
	jQuery(".urr-name-error-span").remove();
	}
	
	var email_val=jQuery('#urr_email').val();
	var regex = /^([a-zA-Z0-9_.+-])+\@(([a-zA-Z0-9-])+\.)+([a-zA-Z0-9]{2,4})+$/;    
	if(!regex.test(email_val)){    
	jQuery(".urr-email-error-span").remove();
		jQuery('.urr-Email-div').append('<span class="urr-email-error-span" style="color: #ff0000;"><br/>Enter a valid Email</span>');
		error_flag= false;    
	}   
	else{
	jQuery(".urr-email-error-span").remove();
	}
		return error_flag;
	});
});
