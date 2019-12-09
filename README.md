# ga-access-exclusion
Script for admin access exclusion in Google Analytics

## How It Works

### 1. Create a Custom Dimension in Google Analytics

  * Name: Access Exclusions
  * Scope: User 

### 2. Create a Filter in Google Analytics. 
  
  * Filter Name: Admin Access Exclusion
  * Filter Type: Custom
  * Filter Field: Access Exclusions
  * Filter Pattern: admin

### 3. access_exclusion.html

Place `access_exclusion.html` in your root directory.

### 4. That's it!

Step `/access_exclusion.html` before access your website so that your access will be excluded in Google Analytics.
