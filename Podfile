source 'https://github.com/CocoaPods/Specs.git'

platform :ios, '8.0'

use_frameworks!

workspace 'LDSAnnotations'
xcodeproj 'LDSAnnotations.xcodeproj'

target 'LDSAnnotations' do
    pod 'PSOperations'
    pod 'SQLite.swift'
    pod 'Swiftification'
    pod 'Locksmith'
end

target 'LDSAnnotationsTests' do
    # Required by LDSAnnotations
    pod 'PSOperations'
    pod 'SQLite.swift'
    pod 'Swiftification'
    pod 'Locksmith'
end

target 'LDSAnnotationsDemo' do
    xcodeproj 'LDSAnnotationsDemo.xcodeproj'
    
    # Required by LDSAnnotations
    pod 'PSOperations'
    pod 'SQLite.swift'
    pod 'Swiftification'
    pod 'Locksmith'
end
