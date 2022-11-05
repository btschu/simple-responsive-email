# simple-responsive-email

```html
<!DOCTYPE html>
<html lang="en">

<head>
	<meta name="viewport" content="width=device-width">
	<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
	<title>HTML EMAIL</title>
</head>

<body
	style="background-color: #f6f6f6; font-family: sans-serif; -webkit-font-smoothing: antialiased; font-size: 14px; line-height: 1.4; margin: 0; padding: 0; -ms-text-size-adjust: 100%; -webkit-text-size-adjust: 100%;">
	<table border="0" cellpadding="0" cellspacing="0" class="body" <tr>
		<td style="font-family: sans-serif; font-size: 14px; vertical-align: top;" valign="top">&nbsp;</td>
		<td class="header"
			style="border-collapse: separate; mso-table-lspace: 0pt; mso-table-rspace: 0pt; color: #FFF; padding: 0px; border-radius: 0px 0px 0px 0px; width: 100%;"
			width="100%">

			<div class="content"
				style="box-sizing: border-box; display: block; Margin: 0 auto; max-width: 580px; padding: 10px;">

				<!--First Section-->
				<!-- ******change background to #ffffff if I want it transparent -->
				<table class="main" border="0" cellpadding="0" cellspacing="0"
					style="border-collapse: separate; mso-table-lspace: 0pt; mso-table-rspace: 0pt; background: #e7e6e6; border-radius: 5px; width: 100%; margin: 20px 0px 0px 0px;"
					width="100%">
					<tr>
						<td class="wrapper"
							style="font-family: sans-serif; font-size: 14px; vertical-align: top; box-sizing: border-box; padding: 20px;"
							valign="top">

							<table border="0" cellpadding="0" cellspacing="0"
								style="border-collapse: separate; mso-table-lspace: 0pt; mso-table-rspace: 0pt; width: 100%;"
								width="100%">
								<tr>
									<!--****** add this after the <td below to center text    <td align="center"-->
									<td style="font-family: sans-serif; font-size: 14px; vertical-align: top;"
										valign="top">
										<!-- ****** uncomment for a header -->
										<!-- <h2 style="color: #212121; font-family: sans-serif; margin-bottom: 30px;">
											Blog Post of The Month</h2> -->
										<p
											style="color: #212121; font-family: sans-serif; font-size: 16px; font-weight: normal; margin: 0; margin-bottom: 15px;">
											Hello,<br>
											I am just testing this email thing to see if it works. <br><br>
											Here is a list of items:
										</p>
										<ul
											style="color: #212121; font-family: sans-serif; font-size: 16px; font-weight: normal; margin: 0; margin-bottom: 15px;">
											<li>list item</li>
											<li>list item</li>
											<li>list item</li>
											<li>list item</li>
										</ul>
										<!-- <p
											style="color: #212121; font-family: sans-serif; font-size: 16px; font-weight: normal; margin: 0; margin-bottom: 15px;">
											Let me know what you think!
										</p> -->

										<!--*** uncomment to add a button-->
										<!-- <table border="0" cellpadding="0" cellspacing="0" class="btn btn-primary"
												style="border-collapse: separate; mso-table-lspace: 0pt; mso-table-rspace: 0pt; box-sizing: border-box; width: 100%;"
												width="100%">
												<tbody>
													<tr>
														<td align="center"
															style="font-family: sans-serif; font-size: 14px; vertical-align: top; padding: 15px 0px 15px 0px;"
															valign="top">
															<table border="0" cellpadding="0" cellspacing="0"
																style="border-collapse: separate; mso-table-lspace: 0pt; mso-table-rspace: 0pt; width: auto;">
																<tbody>
																	<tr>
																		<td style="font-family: sans-serif; font-size: 14px; vertical-align: top; border-radius: 5px; text-align: center; background-color: #fff;"
																			valign="top" align="center" bgcolor="#fff">
																			<a href="#"
																				style="box-shadow: 0px 4px 15px 0px rgba(29, 29, 29, 0.3); border: solid 1px #ffffff; border-radius: 5px; box-sizing: border-box; cursor: pointer; display: inline-block; font-size: 14px; font-weight: bold; margin: 0; padding: 12px 25px; text-decoration: none; text-transform: capitalize; background-color: #fff; border-color: #ffffff; color: #ab6aac;">Read
																				More
																			</a>
																		</td>
																	</tr>
																</tbody>
															</table>
														</td>
													</tr>
												</tbody>
											</table> -->
										<!-- <p
											style="color: #212121; font-family: sans-serif; font-size: 16px; font-weight: normal; margin: 0; margin-bottom: 15px;">
											Thanks,<br>Brandon Schumacher
										</p> -->

										<!-- Signature -->
										<table style="font-family: Helvetica, sans-serif;" cellpadding="0"
											cellspacing="0">
											<tbody>
												<tr>
													<!-- ==================== SECTION #2 ==================== -->
													<table style="font-family: inherit" cellpadding="0" cellspacing="0">
														<tbody>
															<!-- I. Name and status -->
															<tr>
																<td style="font-family: inherit; padding-bottom: 2px; vertical-align: top;"
																	valign="top">
																	<p
																		style="color: #212121; font-family: sans-serif; font-size: 16px; font-weight: normal; margin: 0; margin-bottom: 15px;">
																		Thanks,
																	</p>
																	<h2
																		style="color: #212121; font-family: sans-serif; margin-bottom: 0;">
																		Brandon Schumacher
																	</h2>
																</td>
															</tr>

															<!-- II. School -->
															<tr>
																<td style="font-family: inherit; padding-bottom: 6px; vertical-align: top;"
																	valign="top">
																	<strong>
																		<a
																			style="font-family: inherit; color:#666666; font-size: 11pt; text-decoration: none;">
																			Band Director<br>
																		</a>
																	</strong>
																	<p
																		style="color: #212121; font-family: sans-serif; font-size: 13px; font-weight: normal; margin-top: 0; margin-bottom: 0;">
																		Johnson Junior High School<br>
																		South High School
																	</p>
																</td>
															</tr>

															<!-- III. Contacts -->
															<tr>
																<td style="font-family: inherit; font-size: 10pt; padding-bottom: 4px; line-height: 18px; vertical-align: top; width: 165px;"
																	valign="top">
																	<!-- Email -->
																	<span
																		style="font-family: inherit; color: #0b3d0d;">Email:
																	</span>
																	<a style="font-family: inherit; text-decoration: none; color: #666666;"
																		href="mailto:brandon.schumacher@laramie1.org">
																		brandon.schumacher@laramie1.org
																	</a>
																	<br>
																	<!-- Phone -->
																	<span
																		style="font-family: inherit; color: #0b3d0d;">Phone:
																	</span>
																	<a style="font-family: inherit; text-decoration: none; color: #666666;"
																		href="tel:+3077712640">
																		(307)771-2640 ext. 80408
																	</a>
																	<br>
																</td>
															</tr>

															<!-- IV. Links -->
															<tr>
																<td style="font-family: inherit; width: 500px; padding-top: 2px; padding-left: 0; text-align: left;"
																	valign="left" width="200">




																</td>
															</tr>
														</tbody>
													</table>
												</tr>
											</tbody>
										</table>
									</td>
								</tr>
							</table>
						</td>
					</tr>
					<!--End of the First Section-->
				</table>




				<!--Start of the Footer-->
				<!-- START FOOTER -->
				<!-- <div class="footer" style="clear: both; margin-top: 20px; padding: 10px; background-color: #2B193D; text-align: center; width: 100%;">
              <table border="0" cellpadding="0" cellspacing="0" style="border-collapse: separate; mso-table-lspace: 0pt; mso-table-rspace: 0pt; width: 100%;" width="100%">
                <tr>
                  <td class="content-block" style="font-family: sans-serif; vertical-align: top; color: #d3dce6; font-size: 12px; text-align: center;" valign="top" align="center">
                    <span class="apple-link" style="color: #d3dce6; font-size: 12px; text-align: center;">You're receiving this email because you are subscribed to the TEKDSGNS newsletter.</span>
                    <br> Don't like these emails? <a href="#" style="text-decoration: underline; color: #d3dce6; font-size: 12px; text-align: center;">Unsubscribe</a>.
                  </td>
                </tr>
                <tr>
                  <td class="content-block powered-by" style="font-family: sans-serif; vertical-align: top; color: #d3dce6; font-size: 12px; text-align: center;" valign="top" align="center">
                    Created by <a href="http://tekdsgns.com" style="color: #d3dce6; font-size: 12px; text-align: center; text-decoration: none;">TEKDSGNS</a>.
                  </td>
                </tr>
              </table>
            </div> -->
				<!--End of the Footer-->
			</div>
		</td>
		<td style="font-family: sans-serif; font-size: 14px; vertical-align: top;" valign="top">&nbsp;</td>
		</tr>
	</table>
</body>

</html>
```
