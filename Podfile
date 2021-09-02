platform :ios, "9.0"

use_frameworks!
inhibit_all_warnings!

AWS_SDK_VERSION = "2.19.1"

target "AWSAppSync" do
  pod "AWSCore", '= 2.19.1'
  pod "SQLite.swift", "~> 0.12.2"
  pod "ReachabilitySwift", '~> 4.3.0'
  pod "AppSyncRealTimeClient", "~> 1.4"

  pod "SwiftLint"
end

target "AWSAppSyncTestCommon" do
  pod "AWSS3", '= 2.19.1'
  pod "ReachabilitySwift", '~> 4.3.0'
  # We directly access a database connection to verify certain initialization
  # setups
  pod "SQLite.swift", "~> 0.12.2"
  pod "AppSyncRealTimeClient", "~> 1.4"
end

target "AWSAppSyncTestApp" do
  pod "AWSS3", '= 2.19.1'
  pod "AWSMobileClient", '= 2.19.1'
end

target "AWSAppSyncTestHostApp" do
end

target "AWSAppSyncUnitTests" do
end

target "AWSAppSyncIntegrationTests" do
end

target "ApolloTests" do
  pod "AWSCore", '= 2.19.1'
end
