# Generated by gem2arch
# Maintainer: LeeF

_gemname=rails
pkgname=ruby-enterprise-rails-235
pkgver=2.3.5
pkgrel=1
pkgdesc="Web-application framework with template engine, control-flow layer, and ORM."
arch=('i686' 'x86_64')
url="http://www.rubyonrails.org"
license=('MIT')
depends=('ruby-enterprise' 'ruby-enterprise-rake' 'ruby-enterprise-activesupport-235' 'ruby-enterprise-activerecord-235' 'ruby-enterprise-actionpack-235' 'ruby-enterprise-actionmailer-235' 'ruby-enterprise-activeresource-235')
makedepends=('ruby-enterprise')
source=(http://gems.rubyforge.org/gems/$_gemname-$pkgver.gem)
noextract=($_gemname-$pkgver.gem)
md5sums=('d09038cee224b1a51ae50eff772cd8f2')

build() {
  cd $srcdir
  local _gemdir=`ruby -rubygems -e'puts Gem.default_dir'`
  gem install --ignore-dependencies --no-rdoc --no-ri -i "$pkgdir$_gemdir" $_gemname-$pkgver.gem
}
