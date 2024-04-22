As the designated data scientists for this study, we have been tasked with addressing the challenges surrounding the current standby-duty plan within Berlin’s red-cross rescue service. The aim is to leverage predictive models to enhance HR planning logic. Presently, the daily operations involve a certain number of rescue drivers on duty. However, unexpected factors such as short-term sickness or a surge in emergency calls often necessitate more drivers than initially anticipated. Consequently, a pool of standby-drivers remain on call and are activated when needed, totaling 90 drivers each day.

Several issues with the current planning system have been highlighted, such as:

· Seasonal patterns, like increased sickness during winter months, are not accounted for in our current approach.
· Instances where even with all 90 standby-drivers activated shortages are still faced, leading to the recall of drivers on their days off.
· Having a daily fixed number of standbys is not efficient because there are days with too many standbys followed by days with not enough standbys. It is suggested a more dynamical standby allocation, which takes seasonal patterns into account.

After analyzing the time series data and determining the patterns, created a sinusoidal simulation function to predict the needs.
