pipeline {
    agent any
    options { timestamps() }
    environment {
        IMAGE = 'ranimbenkhali/monapp'  # ⭐ CHANGED! Use your exact username
        TAG = "build-${env.BUILD_NUMBER}"
    }
    # ... rest of your pipeline stays the same
}
