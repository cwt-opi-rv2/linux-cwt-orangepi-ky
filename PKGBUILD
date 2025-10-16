# Maintainer: Chaiwat Suttipongsakul <cwt@bashell.com>

pkgbase=linux-cwt-6.6-orangepi
_variant=cwt
pkgver=6.6.ky
epoch=1 #Based on cwt image version
pkgrel=3
_desc='Linux 6.6.x (-cwt) for Orange Pi RV2 Board'
url='https://github.com/orangepi-xunlong/linux-orangepi'
arch=(riscv64)
license=('GPL2')
makedepends=(bc libelf pahole cpio perl tar xz gcc)
options=('!strip')
_commit='ae9e974d3e19f460b6397bfe8f0f1417a073ce05'
_srcname="linux-orangepi-${_commit}"
source=("${_srcname}.tar.gz::https://github.com/orangepi-xunlong/linux-orangepi/archive/${_commit}.tar.gz"
	'linux-01-enable_pxa_pwm_on_ky_x1.patch'
	'linux-02-add_DMA_BUF_ns_import_to_amvx.patch'
	'linux-03-enable-ky_x1-clocksource.patch'
	'linux-04-fix-timer-ky_x1-conflict-types.patch'
	'https://cdn.kernel.org/pub/linux/kernel/v6.x/incr/patch-6.6.63-64.xz'
	'https://cdn.kernel.org/pub/linux/kernel/v6.x/incr/patch-6.6.64-65.xz'
	'https://cdn.kernel.org/pub/linux/kernel/v6.x/incr/patch-6.6.65-66.xz'
	'https://cdn.kernel.org/pub/linux/kernel/v6.x/incr/patch-6.6.66-67.xz'
	'https://cdn.kernel.org/pub/linux/kernel/v6.x/incr/patch-6.6.67-68.xz'
	'https://cdn.kernel.org/pub/linux/kernel/v6.x/incr/patch-6.6.68-69.xz'
	'https://cdn.kernel.org/pub/linux/kernel/v6.x/incr/patch-6.6.69-70.xz'
	'https://cdn.kernel.org/pub/linux/kernel/v6.x/incr/patch-6.6.70-71.xz'
	'https://cdn.kernel.org/pub/linux/kernel/v6.x/incr/patch-6.6.71-72.xz'
	'https://cdn.kernel.org/pub/linux/kernel/v6.x/incr/patch-6.6.72-73.xz'
	'https://cdn.kernel.org/pub/linux/kernel/v6.x/incr/patch-6.6.73-74.xz'
	'https://cdn.kernel.org/pub/linux/kernel/v6.x/incr/patch-6.6.74-75.xz'
	'config'
	'linux.preset'
	'90-linux.hook')
b2sums=('e924a058b8ef8c8657efa3be3db98869126fb149035318e15ff046927c50d9d6f4f5c8cb570197974ca713affdc8f960fff42970895e38e9da136f9711af94ac'
        '5baf70ff6c10d8499c90572a5ea68e4759faa6a3b9924cf09f4dd469340b3c1d9f2dacc26a1b8d5b0bd518d5ed542cb84dbcf6a0e195205ad5b167580fe0203c'
        'd305273d0efd17979d00658dd1d89de54b18f379cebdf46e04bafd2a335a971433069eea89daa3fa19f82daa773592a62cd300c6c8fe26e66f34648f4d609cd6'
        'e6e155e1b948cea431f3988ee51a31287d35e3c503307119968b69a122e6c19ccab1eab57e697ed1e9cd142ddb8351e96e7c326dc10978ac112509ff8723277c'
        'e1b279543cd644ada4f22f0a19a8a184055ec9676d2f17953b7f2001c4ec6f01df7af420366c7086a0522155ee0437a8d1334930bdab26634a405335d2c77a23'
        'fbac780711077fcf254ca6f46903ff5c958b0fd119130f3660b53283791a7a9e40060077cfe1a9a0436f1e649e61159e0352afe44a43c9d6b17c262a80e8738f'
        '5aa7ed4a8f289fe844f53f1178c0147749ab4a7471010291f4aa75cfdd7ce1361487f56d08c6f7612bda57a7a90fcd9516c4bccc79d831c0ef92e401ff5f4bab'
        '1363c98dc5ab59e87dc6c713cca4fbee5588f80e87544dfe2e6f916fcfd6c71706553f6de0be762154a3e92230d8671940fed941e031e03c867b86d2236318dc'
        '4b005211271cf3c2c1ca640ee0305d468c22300afdb1deeef1afe8678b3f0d536855a9336e260f55f7e4b4da70e83309496b227c837e5f0263e663231c5f6e49'
        '128eb85c748b04002936ebf47e02a3bca53706493739e6369727abe216c90949e1127af35f05d9216547685e1e5f59d70a116951790b046e50e6ec21cb996474'
        '2815d71964ee11b7f84b8d7280ea0d408c6e9b507670c23a3ea906a423754aa350e4ae3501123bdfd25e34d664c25829015e731c0e480700e5a6de4cb2be1442'
        '9f5fd93610caf92f6e39e34cec79782648645aeada191723d63ae5c97f5dd97f28af1b672f097a126338b79c39c861ec7e1a731edd88bea3cbd458bb09466dae'
        'b4196fb0e864cce22cbd1e2e5da3675d0e9f70a63c5f773e9dfa95052efbba77a1fc10dbb28dc27b5c88f98336d4604db7580f9ba33892011e2a663f8afd7bff'
        'c56245c69a361c082b07e74a2cc1d86590d2b2b058a5a670279cfe54f1689bef2c6fa9b3ff6d2128fc573fa0a4bbf143db37216f81a19b08c11003a70254c0ee'
        '41d7640ccbee16bf5a6b05fc465372a34f41d8f98add3ba74a217455bb1f5c14819a7f83655c91be54e3b161dbc646f55d9c13ca764bf686d8add66c4fa4db37'
        'be2307f42a9fd0a36b86d2cb0b9cf3f7520954479b7db7d4287bf41bf34811f7e140b6a74ce49fe355e72d7401e07d052d3362dab418c0f0d787c0decdf8a992'
        '195dde44b44b153741c7d8d115924bf3cb96ed22d84f46c018c24000bf8ad6e6b8895715fd0f4e789db58a7795a5bfdad23230755b7e9b3207adcfbb62bcc37c'
        '9e90fd0d9a99927682a09563e0293e8c9d2454d9ddc0bdbb6444c5befab56d20b78d5ea932df00d87f58f895957cc42a1dfeda837488a1c2aba08bd225f3b5ea'
        '9409ba7baad96bcebfc926128ac1cd9e04914d3c433ee4f1180bd4d5826c8938e61208504750d577e5c416b6e33ad60f06068725287cc3dc6e6752777804f1f4'
        '93285df515c2dd93a9d178ee3c3da4fbf09834c25750c0cd0c9c244045510a2130d77e283105c03e8dbe27fbc96f83fed0adc390c06750e788cb89d3e3361bc2')

prepare() {
	cd $_srcname

	local src
	for src in $(ls ../linux-*.patch); do
		echo "Applying patch $src..."
		patch -Np1 < "../$src"
	done

	for src in $(ls ../patch-*.xz); do
		echo "Applying patch $src..."
		xzcat "../$src" | patch -Np1 -F3
	done

	echo "Setting version..."
	echo "-${_variant}${epoch}" >localversion.10-variant
	echo "-v${pkgver}" >localversion.20-pkgver
	echo "-${pkgrel}" >localversion.30-pkgrel

	echo "Setting config..."
	cp ../config .config

	unset CFLAGS
	if command -v ccache 2>&1 >/dev/null; then 
		CCACHE=$(which ccache 2>/dev/null)
		gcc="${CCACHE} ${CROSS_COMPILE:-}gcc"
	else
		gcc="${CROSS_COMPILE:-}gcc"
	fi

	make -j $(nproc) ARCH=riscv CC="${gcc}" olddefconfig
	cp .config ../../config.new

	make -j $(nproc) ARCH=riscv CC="${gcc}" -s kernelrelease >version
	echo "Prepared $pkgbase version $(<version)"
}

build() {
	cd $_srcname

	unset CFLAGS
	if command -v ccache 2>&1 >/dev/null; then 
		CCACHE=$(which ccache 2>/dev/null)
		gcc="${CCACHE} ${CROSS_COMPILE:-}gcc"
	else
		gcc="${CROSS_COMPILE:-}gcc"
	fi

	make -j $(nproc) ARCH=riscv CC="${gcc}" all
}

_package() {
	pkgdesc="The $_desc kernel and modules"
	depends=(coreutils kmod mkinitcpio ky_x1-firmware)
	optdepends=('wireless-regdb: to set the correct wireless channels of your country'
		'linux-firmware: firmware images needed for some devices')
	provides=("linux=${pkgver}" "WIREGUARD-MODULE")
	conflicts=('linux')

	cd $_srcname
	local kernver="$(<version)"
	local modulesdir="$pkgdir/usr/lib/modules/$kernver"

	echo "Installing boot image..."
	install -Dm644 "arch/riscv/boot/Image.gz" "$modulesdir/vmlinuz"
	install -Dm644 "arch/riscv/boot/Image.gz" "$pkgdir/boot/vmlinuz-$kernver"
	install -Dm644 "System.map" "$pkgdir/boot/System.map-$kernver"

	echo "Installing modules..."
	make -j $(nproc) ARCH=riscv INSTALL_MOD_PATH="$pkgdir/usr" INSTALL_MOD_STRIP=1 modules_install

	echo "Installing dtbs..."
	make -j $(nproc) ARCH=riscv INSTALL_DTBS_PATH="$pkgdir/usr/share/dtbs/$kernver" dtbs_install
	make -j $(nproc) ARCH=riscv INSTALL_DTBS_PATH="$pkgdir/boot/dtbs/" dtbs_install

	# remove build links
	rm "$modulesdir"/build

	install -Dm644 ../linux.preset "${pkgdir}/etc/mkinitcpio.d/linux.preset"
	install -Dm644 ../90-linux.hook "${pkgdir}/usr/share/libalpm/hooks/90-linux.hook"
}

_package-headers() {
	pkgdesc="Headers and scripts for building modules for the $_desc kernel"
	depends=(pahole)
	provides=("linux-headers=${pkgver}")
	conflicts=('linux-headers')

	cd $_srcname
	local builddir="$pkgdir/usr/lib/modules/$(<version)/build"

	echo "Installing build files..."
	install -Dt "$builddir" -m644 .config Makefile Module.symvers System.map version
	install -Dt "$builddir/kernel" -m644 kernel/Makefile
	install -Dt "$builddir/arch/riscv" -m644 arch/riscv/Makefile
	cp -t "$builddir" -a scripts

	# required when DEBUG_INFO_BTF_MODULES is enabled
	cp --parents -r -t "$builddir/" tools/bpf/resolve_btfids

	echo "Installing VDSO files..."
	cp -a --parents -r -t "$builddir" arch/riscv/kernel/vdso/*
	cp -a --parents -r -t "$builddir" lib/vdso/*
	chmod -R g+w "$builddir/arch/riscv/kernel/vdso"

	echo "Installing certificate files..."
	install -Dt "$builddir/certs" -m640 certs/*.pem
	install -Dt "$builddir/certs" -m640 certs/*.x509

	echo "Installing headers..."
	cp -t "$builddir" -a include
	chmod -R g+w "$builddir/include/generated"
	cp -t "$builddir/arch/riscv" -a arch/riscv/include
	install -Dt "$builddir/arch/riscv/kernel" -m644 arch/riscv/kernel/asm-offsets.s

	install -Dt "$builddir/drivers/md" -m644 drivers/md/*.h
	install -Dt "$builddir/net/mac80211" -m644 net/mac80211/*.h

	# https://bugs.archlinux.org/task/13146
	install -Dt "$builddir/drivers/media/i2c" -m644 drivers/media/i2c/msp3400-driver.h

	# https://bugs.archlinux.org/task/20402
	install -Dt "$builddir/drivers/media/usb/dvb-usb" -m644 drivers/media/usb/dvb-usb/*.h
	install -Dt "$builddir/drivers/media/dvb-frontends" -m644 drivers/media/dvb-frontends/*.h
	install -Dt "$builddir/drivers/media/tuners" -m644 drivers/media/tuners/*.h

	# https://bugs.archlinux.org/task/71392
	install -Dt "$builddir/drivers/iio/common/hid-sensors" -m644 drivers/iio/common/hid-sensors/*.h

	echo "Installing KConfig files..."
	find . -name 'Kconfig*' -exec install -Dm644 {} "$builddir/{}" \;

	echo "Removing unneeded architectures..."
	local arch
	for arch in "$builddir"/arch/*/; do
		[[ $arch = */riscv/ ]] && continue
		echo "Removing $(basename "$arch")"
		rm -r "$arch"
	done

	echo "Installing RAS from x86..."
	install -Dt "$builddir/arch/x86/ras"	-m644 arch/x86/ras/Kconfig

	echo "Removing documentation..."
	rm -r "$builddir/Documentation"

	echo "Removing broken symlinks..."
	find -L "$builddir" -type l -printf 'Removing %P\n' -delete

	echo "Removing loose objects..."
	find "$builddir" -type f -name '*.o' -printf 'Removing %P\n' -delete

	echo "Stripping build tools..."
	local file
	while read -rd '' file; do
		case "$(file -bi "$file")" in
		application/x-sharedlib\;*) # Libraries (.so)
			strip -v $STRIP_SHARED "$file" ;;
		application/x-archive\;*) # Libraries (.a)
			strip -v $STRIP_STATIC "$file" ;;
		application/x-executable\;*) # Binaries
			strip -v $STRIP_BINARIES "$file" ;;
		application/x-pie-executable\;*) # Relocatable binaries
			strip -v $STRIP_SHARED "$file" ;;
		esac
	done < <(find "$builddir" -type f -perm -u+x ! -name vmlinux -print0)

	echo "Adding symlink..."
	mkdir -p "$pkgdir/usr/src"
	ln -sr "$builddir" "$pkgdir/usr/src/$pkgbase"
}

pkgname=("$pkgbase" "$pkgbase-headers")
for _p in "${pkgname[@]}"; do
	eval "package_$_p() {
		$(declare -f "_package${_p#$pkgbase}")
		_package${_p#$pkgbase}
	}"
done

