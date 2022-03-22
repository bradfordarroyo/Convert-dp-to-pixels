# Convert-dp-to-pixels
Convert dp to pixels
public static int convertDpToPixel(int dp) {
     Resources r = Resources.getSystem();
     return Math.round(dp * (r.getDisplayMetrics().densityDpi / 160f));
}
