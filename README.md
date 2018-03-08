thebanchan site

### Rolling Banner Tag ###
----

- PC
```html
<li style="background-image: url('{{your_image_url}}'); background-color: rgb(238, 238, 238); z-index: 1; opacity: 0;" class="">
	<a href="javascript:void(0);" 
	onclick="overpass.tracking.link({ openwinyn:'N', tr_yn:'Y', banner_kind_cd:'90', conts_form_cd:'130', conts_form_dtl_cd:'13010', conts_divi_cd:'', conts_dist_no:'', sale_area_no:'D1706000841', rel_divi_cd:'20', rel_no:'171100000005752', move_cont_no:'', url:'{{target_url}}', param:''});">
		<span class="ir">{{title}}</span>
	</a>
</li>
```

- Mobile
```html
<li class="swiper-slide" style="width: 640px; height: 400px;">
	<a href="javascript:void(0);" onclick="overpass.tracking.link({ openwinyn:'N', tr_yn:'Y', banner_kind_cd:'90', conts_form_cd:'130', conts_form_dtl_cd:'13010', conts_divi_cd:'', conts_dist_no:'', sale_area_no:'D1705000782', rel_divi_cd:'20', 	rel_no:'180300000006442', move_cont_no:'', url:'{{target_url}}', param:''});">
		<img src="{{your_image_url}}" class="" alt="{{title}}">
	</a>
</li>
```