URLS

Here are the urls for each of the pages
https://infs3202-32ffc8f9.uqcloud.net/fittrack/login/
https://infs3202-32ffc8f9.uqcloud.net/fittrack/trainer/create-workout/
https://infs3202-32ffc8f9.uqcloud.net/fittrack/trainer/dashboard/
https://infs3202-32ffc8f9.uqcloud.net/fittrack/trainer/assign-workout/
https://infs3202-32ffc8f9.uqcloud.net/fittrack/client/log-workout/
https://infs3202-32ffc8f9.uqcloud.net/fittrack/qr-entry/

The url patterns if the specific link does not work
urlpatterns = [
    path("", views.login, name="login"),
    path("login/", views.login, name="login"),
    path("trainer/dashboard/", views.trainer_dashboard, name="trainer_dashboard"),
    path("trainer/create-workout/", views.create_workout, name="create_workout"),
    path("trainer/assign-workout/", views.assign_workout, name="assign_workout"),
    path("client/log-workout/", views.log_workout, name="log_workout"),
    path("qr-entry/", views.qr_entry, name="qr_entry")
]
