hallo_world
===========

Testing 1
<!-- CHANGE -->
<?php if ($show_social) { ?>
					
					<div class="share-links clearfix">
						<div class="share-text"><?php _e("Share:", "swiftframework"); ?></div>
						<div class="share-buttons">
							<span class='st_facebook_hcount' displayText='Facebook'></span>
							<!--<span class='st_linkedin_hcount' displayText='LinkedIn'></span>
							<span class='st_pinterest_hcount' displayText='Pinterest'></span>--><br/><br/>
						</div>
						<a class="permalink item-link" href="<?php the_permalink(); ?>"><i class="icon-link"></i><?php _e("Permanent Link", "swiftframework"); ?></a>
						<a class="email-link item-link" href="mailto:?subject=<?php the_title(); ?>&amp;body=<?php the_permalink(); ?>" title="Share by Email"><i class="icon-envelope-alt"></i><?php _e("Share via Email", "swiftframework"); ?></a>						
					</div>
					
					<?php } ?>
<!-- CHANGE -->
