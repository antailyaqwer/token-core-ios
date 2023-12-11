platform :ios, "9.3"

target "TokenCore" do
  use_frameworks! :linkage => :static

  pod "CryptoSwift", ">= 0.10.0"
  pod "BigInt", "3.0.0"

  pod 'SwiftLint'

  pod "CoreBitcoin", git: "https://github.com/antailyaqwer/CoreBitcoin.git", branch: "master"

  target "TokenCoreTests" do
    inherit! :search_paths
  end
end